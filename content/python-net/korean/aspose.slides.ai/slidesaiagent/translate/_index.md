---
title: translate method
second_title: Aspose.Slides Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
AI를 사용하여 프레젠테이션을 지정된 언어로 변환합니다 (동기식 버전).


```python
def translate(self, presentation, language):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) | 대상 프레젠테이션 |
| language | **str** | 대상 언어 |

### 비고

아래 예제는 기본 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용합니다. 이 객체는 매개변수가 없는 **SlidesAIAgent.#ctor** 생성자를 통해 생성되며 Aspose 자체 LLM에 연결됩니다. 다른 AI 공급자를 사용하려면 자체 LLM을 제공하거나 연결을 사용자 지정하십시오(예: 자체 `HttpClient`를 제공). **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 생성자에 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현을 전달하십시오. 사용 가능한 구현은 다음과 같습니다:

* [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation 인스턴스가 제공되지 않음 |
| **RuntimeError(Proxy error(ArgumentException))** | Language 값이 None이거나 비어 있을 수 없음 |



### 참조
* 클래스 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* 클래스 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)
* 클래스 [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* 클래스 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)