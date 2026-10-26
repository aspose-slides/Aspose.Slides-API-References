---
title: copy_to method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Копирует элементы из **System.Collections.Generic.ICollection`1** в **System.Array**, начиная с определённого индекса **System.Array**.



```python
def copy_to(self, array, array_index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| array | **List[IParagraph]** | Одномерный **System.Array**, который является получателем элементов, скопированных из **System.Collections.Generic.ICollection`1**. **System.Array** должен иметь индексацию, начинающуюся с нуля. |
| array_index | **int** | Нулевой индекс в `array`, с которого начинается копирование. |

### Exceptions

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` является None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` меньше 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Количество элементов в исходном **System.Collections.Generic.ICollection`1** больше доступного места от `array_index` до конца целевого `array`. |



### See Also
* класс [`ParagraphCollection`](/slides/python-net/ru/aspose.slides/paragraphcollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)