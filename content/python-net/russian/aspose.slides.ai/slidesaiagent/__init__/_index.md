---
title: SlidesAIAgent constructor
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Инициализирует новый экземпляр [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent) с использованием встроенного [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient) с его конфигурацией по умолчанию. Клиент подключается к собственному LLM Aspose и не требует дополнительной конфигурации. Чтобы использовать другой AI-клиент, используйте перегрузку **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** вместо этого.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Инициализирует новый экземпляр [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent) с пользовательским AI-клиентом. Используйте эту перегрузку для указания поставщика AI, предоставления собственного LLM или настройки соединения (например, предоставив свой `HttpClient`). Любая реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) может быть использована, включая:

* [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)

Чтобы использовать встроенный [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient) с конфигурацией по умолчанию, используйте перегрузку **SlidesAIAgent.#ctor** вместо этого.

```python
def __init__(self, ai_client):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) | Экземпляр AI-клиента. Любая реализация [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient) может быть использована. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Экземпляр AI-клиента не предоставлен. |

### См. также
* класс [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* класс [`IAIWebClient`](/slides/python-net/ru/aspose.slides.ai/iaiwebclient)
* класс [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)
* класс [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* класс [`SlidesAIAgent`](/slides/python-net/ru/aspose.slides.ai/slidesaiagent)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)