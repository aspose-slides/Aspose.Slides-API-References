---
title: copy_to method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Копирует элементы **System.Collections.Generic.ICollection`1** в **System.Array**, начиная с указанного индекса **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| array | **List[IBehavior]** | Одномерный **System.Array**, являющийся назначением элементов, скопированных из **System.Collections.Generic.ICollection`1**. **System.Array** должен использовать нулевую индексацию. |
| array_index | **int** | Нулевой индекс в `array`, с которого начинается копирование. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` равно None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` меньше 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Количество элементов в исходном **System.Collections.Generic.ICollection`1** превышает доступное пространство от `array_index` до конца целевого `array`. |

### См. также
* класс [`BehaviorCollection`](/slides/python-net/ru/aspose.slides.animation/behaviorcollection)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)