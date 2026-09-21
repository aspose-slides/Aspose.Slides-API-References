---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
빌트인 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)의 새 인스턴스를 초기화합니다
            [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 기본 구성으로 사용합니다. 클라이언트는
            Aspose의 자체 LLM에 연결되며 추가 구성이 필요하지 않습니다.
            다른 AI 클라이언트를 사용하려면 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 오버로드를 대신 사용하십시오.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
[`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)의 새 인스턴스를 사용자 지정 AI 클라이언트와 함께 초기화합니다.
            이 오버로드를 사용하여 AI 공급자를 지정하거나 자체 LLM을 제공하거나 연결을 사용자 정의할 수 있습니다(예: 자체 `HttpClient` 제공).
            [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)의 모든 구현을 사용할 수 있으며, 다음을 포함합니다:

* [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)

            기본 구성을 가진 빌트인 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용하려면, **SlidesAIAgent.#ctor** 오버로드를 대신 사용하십시오.

```python
def __init__(self, ai_client):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) | AI 클라이언트 인스턴스. [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)의 모든 구현을 사용할 수 있습니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI 클라이언트 인스턴스가 제공되지 않았습니다. |

### 참고
* 클래스 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* 클래스 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)
* 클래스 [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)
* 클래스 [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* 클래스 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)