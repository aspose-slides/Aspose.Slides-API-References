---
title: aspose.slides.ai
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/
---


Contains classes that provide AI-based features for analyzing and processing PowerPoint presentations.
## Classes

| Class | Description |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient/) | A built-in [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) implementation that connects to Aspose's own LLM.<br/>            This is the default client used by the parameterless **SlidesAIAgent.#ctor** constructor. |
| [`IAIConversation`](/slides/python-net/aspose.slides.ai/iaiconversation/) | Represents a conversation instance. Unlike regular AI calls, conversations retain the entire context. |
| [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient/) | AI Web client interface. This interface enables to substitute different AI language models.<br/>            Classes that implement this interface are supposed to be used along with `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient/) | A built-in [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) implementation that connects to an OpenAI-compatible LLM provider<br/>            at a specified base URL. |
| [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient/) | A built-in [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) implementation that connects to the OpenAI API. |
| [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent/) | Provides AI-powered features for processing presentations. |
| [`SlidesAIAgentException`](/slides/python-net/aspose.slides.ai/slidesaiagentexception/) | Represents Slides AI Agent related exceptions. |

## Enumerations

| Enumeration | Description |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/aspose.slides.ai/presentationcontentamounttype/) | Specifies the amount of content included in the generated presentation, influencing both the number of slides and the level of detail per slide. |

