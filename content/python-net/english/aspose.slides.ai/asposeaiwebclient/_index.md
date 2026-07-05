---
title: AsposeAIWebClient class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/asposeaiwebclient/
---


## AsposeAIWebClient class

A built-in [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) implementation that connects to Aspose's own LLM.
            This is the default client used by the parameterless **SlidesAIAgent.#ctor** constructor.

The AsposeAIWebClient type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.ai/asposeaiwebclient/__init__/#) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint.<br/>            This is the client used by the parameterless **SlidesAIAgent.#ctor** constructor, so creating<br/>            it explicitly is only required when passing the client to the **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            constructor directly. |
| [`__init__`](/slides/python-net/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. Use this<br/>            overload when you have a URL provided by the Aspose.Slides team; otherwise, use the<br/>            **AsposeAIWebClient.#ctor** overload with the default URL. |

## Methods

| Method | Description |
| :- | :- |
| [`create_conversation`](/slides/python-net/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Creates a conversation instance. Unlike regular AI calls, conversations retain the entire context. |


### See Also
* class [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

