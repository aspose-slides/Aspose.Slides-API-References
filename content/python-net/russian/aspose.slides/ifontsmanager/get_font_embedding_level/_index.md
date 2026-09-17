---
title: get_font_embedding_level method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Определяет уровень встраивания шрифта из заданного массива байтов и имени шрифта.

### Возвращаемое значение

Уровень встраивания указанного шрифта.



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
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, когда `font_bytes` равен None. |



### См. также
* перечисление [`EmbeddingLevel`](/slides/python-net/ru/aspose.slides/embeddinglevel)
* класс [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)