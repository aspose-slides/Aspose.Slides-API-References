---
title: get_font_embedding_level method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Определяет уровень внедрения шрифта из указанного массива байтов и имени шрифта.

### Возвращаемое значение

Уровень внедрения указанного шрифта.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| font_bytes | **bytes** | Массив байтов, содержащий данные шрифта. |
| font_name | **str** | Имя шрифта. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, когда `font_bytes` равно None. |



### См. также
* перечисление [`EmbeddingLevel`](/slides/python-net/ru/aspose.slides/embeddinglevel)
* класс [`FontsManager`](/slides/python-net/ru/aspose.slides/fontsmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)