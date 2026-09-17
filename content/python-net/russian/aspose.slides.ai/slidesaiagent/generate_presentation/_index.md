---
title: generate_presentation method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Создает экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| description | **str** | Тема, идеи, цитаты или фрагменты текста. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ru/aspose.slides.ai/presentationcontentamounttype) | Объём содержимого в получаемой презентации. |

### Примечания

Пример ниже использует значение по умолчанию [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient), которое создаётся конструктором без параметров **SlidesAIAgent.#ctor** и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика ИИ, предоставьте свой LLM или настройте соединение (например, предоставив собственный `HttpClient`), передайте реализацию [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) в конструктор **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Доступные реализации включают:
             
* [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Инструкция чата ИИ не может быть None или пустой. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Создает экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| description | **str** | Тема, идеи, цитаты или фрагменты текста. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/ru/aspose.slides.ai/presentationcontentamounttype) | Объём содержимого в получаемой презентации. |
| presentation_template | [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) | Презентация, используемая в качестве шаблона для макета и дизайна, заменяющая шаблон по умолчанию. |

### Примечания

Пример ниже использует значение по умолчанию [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient), которое создаётся конструктором без параметров **SlidesAIAgent.#ctor** и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика ИИ, предоставьте свой LLM или настройте соединение (например, предоставив собственный `HttpClient`), передайте реализацию [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) в конструктор **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Доступные реализации включают:
            
* [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Шаблон презентации не предоставлен. |
| **RuntimeError(Proxy error(ArgumentException))** | Инструкция чата ИИ не может быть None или пустой. |



### См. также
* класс [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* класс [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* класс [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)
* класс [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* перечисление [`PresentationContentAmountType`](/slides/python-net/ru/aspose.slides.ai/presentationcontentamounttype)
* класс [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)