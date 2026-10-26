---
title: copy_to method
second_title: Aspose.Slides для Python через .NET — справочник API
description: 
type: docs
url: /ru/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Копирует элементы **System.Collections.Generic.ICollection`1** в **System.Array**, начиная с указанного индекса **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| array | **List[IPortion]** | Одномерный **System.Array**, являющийся получателем элементов, скопированных из **System.Collections.Generic.ICollection`1**. **System.Array** должен использовать индексацию, начинающуюся с нуля. |
| array_index | **int** | Нулевой индекс в `array`, с которого начинается копирование. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` равно None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` меньше 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Количество элементов в исходном **System.Collections.Generic.ICollection`1** больше доступного места от `array_index` до конца целевого `array`. |



### См. также
* класс [`PortionCollection`](/slides/python-net/ru/aspose.slides/portioncollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)