---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Создает экземпляр совместимого с OpenAI веб-клиента.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| model | **str** | Название модели, поддерживаемой провайдером LLM. |
| api_key | **str** | API-ключ (токен). |
| base_url | **str** | Базовый URL совместимого с OpenAI LLM. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Значение API-ключа не может быть None или пустым. |
| **RuntimeError(Proxy error(ArgumentException))** | Значение текстовой модели не может быть None или пустым. |
| **RuntimeError(Proxy error(ArgumentException))** | Значение базового URL не может быть None или пустым. |



### См. также
* класс [`OpenAICompatibleWebClient`](/slides/python-net/ru/aspose.slides.ai/openaicompatiblewebclient)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)