---
title: translate method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Переводит презентацию на указанный язык с использованием ИИ (синхронная версия).

```python
def translate(self, presentation, language):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) | Целевая презентация |
| language | **str** | Целевой язык |

### Замечания

Пример ниже использует значение по умолчанию [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient), которое создаётся без параметров **SlidesAIAgent.#ctor** и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика ИИ, предоставьте свой LLM или настройте соединение (например, предоставив свой `HttpClient`), передайте реализацию [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) в конструктор **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Доступные реализации включают:

* [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)

### Исключения

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Экземпляр презентации не предоставлен |
| **RuntimeError(Proxy error(ArgumentException))** | Значение языка не может быть None или пустым |

### См. также
* класс [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* класс [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* класс [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)
* класс [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* класс [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)