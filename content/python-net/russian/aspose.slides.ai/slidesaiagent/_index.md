---
title: SlidesAIAgent class
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent класс

Предоставляет функции с поддержкой ИИ для обработки презентаций.

Тип SlidesAIAgent раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Инициализирует новый экземпляр [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent) с пользовательским клиентом ИИ.<br/>            Используйте эту перегрузку, чтобы указать поставщика ИИ, предоставить свой собственный LLM или настроить<br/>            соединение (например, предоставив свой `HttpClient`).<br/>            Можно использовать любую реализацию [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient), включая:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Чтобы использовать встроенный [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient) с его конфигурацией по умолчанию,<br/>            используйте перегрузку **SlidesAIAgent.#ctor** вместо этого. |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/__init__/#) | Инициализирует новый экземпляр [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent), используя встроенный<br/>            [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient) с конфигурацией по умолчанию. Клиент подключается к<br/>            собственному LLM компании Aspose и не требует дополнительной настройки.<br/>            Чтобы использовать другой клиент ИИ, используйте перегрузку **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** вместо этого. |

## Методы

| Метод | Описание |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Создаёт экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Создаёт экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке. |
| [`translate(self, presentation, language)`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Переводит презентацию на указанный язык с помощью ИИ (синхронная версия). |

### См. также
* класс [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* класс [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient)
* класс [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)
* класс [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* класс [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)