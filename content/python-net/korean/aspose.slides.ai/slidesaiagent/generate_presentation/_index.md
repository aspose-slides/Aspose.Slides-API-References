---
title: generate_presentation method
second_title: .NET API 레퍼런스를 통한 Aspose.Slides for Python
description: 
type: docs
url: /ko/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
텍스트 설명에서 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 조각을 제공합니다.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| description | **str** | 주제, 아이디어, 인용문 또는 텍스트 조각. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ko/aspose.slides.ai/presentationcontentamounttype) | 결과 프레젠테이션에 포함되는 콘텐츠 양. |

### 참고

아래 예제는 기본 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용합니다. 이 객체는 매개변수가 없는 **SlidesAIAgent.#ctor** 생성자로 생성되며 Aspose 자체 LLM에 연결됩니다. 다른 AI 제공자를 사용하려면 자체 LLM을 제공하거나 연결을 사용자 지정하고(예: 자체 `HttpClient` 제공) **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 생성자에 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현을 전달하십시오. 사용 가능한 구현에는 다음이 포함됩니다:
             
* [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI 채팅 지시가 None이거나 비어 있을 수 없습니다. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
텍스트 설명에서 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 조각을 제공합니다.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| description | **str** | 주제, 아이디어, 인용문 또는 텍스트 조각. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ko/aspose.slides.ai/presentationcontentamounttype) | 결과 프레젠테이션에 포함되는 콘텐츠 양. |
| presentation_template | [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) | 레이아웃 및 디자인 템플릿으로 사용할 프레젠테이션으로, 기본 템플릿을 대체합니다. |

### 참고

아래 예제는 기본 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용합니다. 이 객체는 매개변수가 없는 **SlidesAIAgent.#ctor** 생성자로 생성되며 Aspose 자체 LLM에 연결됩니다. 다른 AI 제공자를 사용하려면 자체 LLM을 제공하거나 연결을 사용자 지정하고(예: 자체 `HttpClient` 제공) **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 생성자에 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현을 전달하십시오. 사용 가능한 구현에는 다음이 포함됩니다:
            
* [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 프레젠테이션 템플릿이 제공되지 않았습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | AI 채팅 지시가 None이거나 비어 있을 수 없습니다. |

### 참고
* 클래스 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* 클래스 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)
* 클래스 [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* 열거형 [`PresentationContentAmountType`](/slides/python-net/ko/aspose.slides.ai/presentationcontentamounttype)
* 클래스 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)