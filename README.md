# Vertex AI Gemini 1.5 Flash 비용 계산하기

## 개요

Gemini의 경우 [Google AI Studio](https://ai.google.dev/pricing?_gl=1*1l09a21*_up*MQ..*_ga*MTUxNTcxNzY5NS4xNzM1MjAyNjg1*_ga_P1DBVKWT6V*MTczNTIwMjY4NS4xLjAuMTczNTIwMjczMy4wLjAuNzY5MDY2MDAx#1_5flash)와 [Vertex AI](https://cloud.google.com/vertex-ai/generative-ai/pricing)에서 과금하는 체계가 다르다. Google AI Studio에서는 토큰당 과금을 하는 반면, Vertex AI에서는 글자수에 따라 과금을 한다. 이에 따라 과금 방식이 헷갈리는 사용자를 위해서 Gemini 모델에 입력으로 넣는 특정 프롬프트와 출력의 결과를 바탕으로 금액을 계산하는 코드 샘플이다.
