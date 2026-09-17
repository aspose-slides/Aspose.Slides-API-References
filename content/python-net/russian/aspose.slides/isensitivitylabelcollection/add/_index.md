---
title: add method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Добавляет SensitivityLabel в коллекцию.

### Возвращаемое значение

Индекс, по которому SensitivityLabel был добавлен.



```python
def add(self, label):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ru/aspose.slides/isensitivitylabel) | Объект SensitivityLabel, который будет добавлен в конец коллекции. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда SensitivityLabel с тем же Id уже был добавлен. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ru/aspose.slides/sensitivitylabelassignmenttype) |  |



### См. также
* класс [`ISensitivityLabel`](/slides/python-net/ru/aspose.slides/isensitivitylabel)
* класс [`ISensitivityLabelCollection`](/slides/python-net/ru/aspose.slides/isensitivitylabelcollection)
* перечисление [`SensitivityLabelAssignmentType`](/slides/python-net/ru/aspose.slides/sensitivitylabelassignmenttype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)