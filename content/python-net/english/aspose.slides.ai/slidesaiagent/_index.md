---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/slidesaiagent/
---


## SlidesAIAgent class

Provides AI-powered features for processing presentations.

The SlidesAIAgent type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Initializes a new instance of [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent) with a custom AI client.<br/>            Use this overload to specify the AI provider, supply your own LLM, or customize the<br/>            connection (for example, by providing your own `HttpClient`).<br/>            Any implementation of [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) can be used, including:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            To use the built-in [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient) with its default configuration,<br/>            use the **SlidesAIAgent.#ctor** overload instead. |
| [`__init__`](/slides/python-net/aspose.slides.ai/slidesaiagent/__init__/#) | Initializes a new instance of [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent) using the built-in<br/>            [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient) with its default configuration. The client connects to<br/>            Aspose's own LLM and requires no additional configuration.<br/>            To use a different AI client, use the **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload instead. |

## Methods

| Method | Description |
| :- | :- |
| [`generate_presentation`](/slides/python-net/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language. |
| [`generate_presentation`](/slides/python-net/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language. |
| [`translate`](/slides/python-net/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Translates a presentation to the specified language using AI (synchronous version). |


### See Also
* class [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

