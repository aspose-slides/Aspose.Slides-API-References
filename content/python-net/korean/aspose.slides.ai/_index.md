---
title: aspose.slides.ai
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ai/
---
PowerPoint 프레젠테이션을 분석하고 처리하기 위한 AI 기반 기능을 제공하는 클래스를 포함합니다.
## 클래스

| 클래스 | 설명 |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient/) | Aspose 고유의 LLM에 연결되는 내장 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현입니다.<br/>            매개변수가 없는 **SlidesAIAgent.#ctor** 생성자에서 사용되는 기본 클라이언트입니다. |
| [`IAIConversation`](/slides/python-net/ko/aspose.slides.ai/iaiconversation/) | 대화 인스턴스를 나타냅니다. 일반 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다. |
| [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient/) | AI 웹 클라이언트 인터페이스입니다. 이 인터페이스를 사용하면 다양한 AI 언어 모델을 교체할 수 있습니다.<br/>            이 인터페이스를 구현하는 클래스는 `SlidesAIAgent`와 함께 사용해야 합니다. |
| [`OpenAICompatibleWebClient`](/slides/python-net/ko/aspose.slides.ai/openaicompatiblewebclient/) | OpenAI 호환 LLM 제공자에 연결되는 내장 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현입니다.<br/>            지정된 기본 URL에. |
| [`OpenAIWebClient`](/slides/python-net/ko/aspose.slides.ai/openaiwebclient/) | OpenAI API에 연결되는 내장 [`IAIWebClient`](/slides/python-net/ko/aspose.slides.ai/iaiwebclient) 구현입니다. |
| [`SlidesAIAgent`](/slides/python-net/ko/aspose.slides.ai/slidesaiagent/) | 프레젠테이션 처리를 위한 AI 기반 기능을 제공합니다. |
| [`SlidesAIAgentException`](/slides/python-net/ko/aspose.slides.ai/slidesaiagentexception/) | Slides AI Agent와 관련된 예외를 나타냅니다. |

## 열거형

| 열거형 | 설명 |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/ko/aspose.slides.ai/presentationcontentamounttype/) | 생성된 프레젠테이션에 포함되는 콘텐츠 양을 지정하며, 슬라이드 수와 슬라이드당 상세 수준 모두에 영향을 줍니다. |