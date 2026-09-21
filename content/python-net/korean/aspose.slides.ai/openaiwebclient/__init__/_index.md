---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
OpenAI 웹 클라이언트의 인스턴스를 생성합니다.

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| model | **str** | OpenAI 언어 모델. 가능한 값:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API 키. |
| organization_id | **str** | 조직 ID (옵션). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API 키 값은 None이거나 비어 있을 수 없습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 텍스트 모델 값은 None이거나 비어 있을 수 없습니다. |



### 참고
* 클래스 [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)