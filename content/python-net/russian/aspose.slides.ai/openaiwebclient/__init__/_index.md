---
title: OpenAIWebClient constructor
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Создаёт экземпляр веб-клиента OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| model | **str** | Языковая модель OpenAI. Возможные значения:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | API-ключ OpenAI. |
| organization_id | **str** | Идентификатор организации (необязательно). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Значение API-ключа не может быть None или пустым. |
| **RuntimeError(Proxy error(ArgumentException))** | Значение текстовой модели не может быть None или пустым. |



### See Also
* класс [`OpenAIWebClient`](/slides/python-net/ru/aspose.slides.ai/openaiwebclient)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)