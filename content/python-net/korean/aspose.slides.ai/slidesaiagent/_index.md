---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent 클래스

프레젠테이션 처리를 위한 AI 기반 기능을 제공합니다.

SlidesAIAgent 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | 사용자 지정 AI 클라이언트를 사용하여 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)의 새 인스턴스를 초기화합니다.<br/>            이 오버로드를 사용하여 AI 제공자를 지정하고, 자체 LLM을 제공하거나, 연결을 사용자 지정합니다(예: 자체 `HttpClient`를 제공).<br/>            [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)의 모든 구현을 사용할 수 있으며, 포함됩니다:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            기본 구성을 갖춘 내장 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용하려면,<br/>            대신 **SlidesAIAgent.#ctor** 오버로드를 사용하십시오. |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/__init__/#) | [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)의 새 인스턴스를 내장 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)를 사용하여 기본 구성으로 초기화합니다.<br/>            클라이언트는 Aspose의 자체 LLM에 연결되며 추가 구성이 필요하지 않습니다.<br/>            다른 AI 클라이언트를 사용하려면 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 오버로드를 사용하십시오. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 조각을 제공하십시오. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 조각을 제공하십시오. |
| [`translate(self, presentation, language)`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | AI를 사용하여 프레젠테이션을 지정된 언어로 번역합니다(동기 버전). |

### 참고
* 클래스 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* 클래스 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient)
* 클래스 [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient)
* 클래스 [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient)
* 클래스 [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)