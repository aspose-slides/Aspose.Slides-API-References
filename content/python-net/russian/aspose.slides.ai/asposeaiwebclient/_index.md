---
title: AsposeAIWebClient class
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides.ai/asposeaiwebclient/
---
## класс AsposeAIWebClient

Встроенная реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient), которая подключается к собственному LLM Aspose. Это клиент по умолчанию, используемый конструктором без параметров **SlidesAIAgent.#ctor**.

Тип AsposeAIWebClient предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient/__init__/#) | Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке LLM Aspose по умолчанию.<br/>            Это клиент, используемый конструктором без параметров **SlidesAIAgent.#ctor**, поэтому создавать<br/>            его явно требуется только при передаче клиента напрямую в конструктор **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. |
| [`__init__(self, url)`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки. Используйте эту<br/>            перегрузку, когда у вас есть URL, предоставленный командой Aspose.Slides; в противном случае используйте<br/>            перегрузку **AsposeAIWebClient.#ctor** с URL по умолчанию. |

## Методы

| Метод | Описание |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Создает экземпляр беседы. В отличие от обычных вызовов ИИ, беседы сохраняют весь контекст. |

### См. также
* класс [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)