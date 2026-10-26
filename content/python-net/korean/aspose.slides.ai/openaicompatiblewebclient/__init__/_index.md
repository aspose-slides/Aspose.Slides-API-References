---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
OpenAI 호환 웹 클라이언트의 인스턴스를 생성합니다.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| model | **str** | LLM 제공자가 지원하는 모델 이름입니다. |
| api_key | **str** | API 키(토큰). |
| base_url | **str** | OpenAI 호환 LLM의 기본 URL. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API 키 값은 None이거나 비어 있을 수 없습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 텍스트 모델 값은 None이거나 비어 있을 수 없습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | Base URL 값은 None이거나 비어 있을 수 없습니다. |

### 또 보기
* 클래스 [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)