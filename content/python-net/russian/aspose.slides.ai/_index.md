---
title: aspose.slides.ai
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ai/
---
Содержит классы, предоставляющие функции на основе ИИ для анализа и обработки презентаций PowerPoint.
## Классы

| Класс | Описание |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient/) | Встроенная реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient), подключающаяся к собственному LLM Aspose.<br/>            Это клиент по умолчанию, используемый конструктором **SlidesAIAgent.#ctor** без параметров. |
| [`IAIConversation`](/slides/python-net/ru/aspose.slides.ai/iaiconversation/) | Представляет экземпляр беседы. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст. |
| [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient/) | Интерфейс AI Web клиента. Этот интерфейс позволяет заменять разные модели языкового ИИ.<br/>            Классы, реализующие этот интерфейс, должны использоваться совместно с `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient/) | Встроенная реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient), подключающаяся к совместимому с OpenAI поставщику LLM<br/>            по указанному базовому URL. |
| [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient/) | Встроенная реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient), подключающаяся к API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/) | Предоставляет функции на базе ИИ для обработки презентаций. |
| [`SlidesAIAgentException`](/slides/python-net/ru/aspose.slides.ai/slidesaiagentexception/) | Представляет исключения, связанные с Slides AI Agent. |

## Перечисления

| Перечисление | Описание |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/ru/aspose.slides.ai/presentationcontentamounttype/) | Определяет количество контента, включаемого в сгенерированную презентацию, влияя как на число слайдов, так и на уровень детализации каждого слайда. |