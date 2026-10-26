---
title: add method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Добавляет SensitivityLabel в коллекцию.

### Возвращаемое значение

Индекс, в котором был добавлен SensitivityLabel.



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
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда метка чувствительности с тем же Id уже была добавлена. |


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



### Смотрите также
* класс [`ISensitivityLabel`](/slides/python-net/ru/aspose.slides/isensitivitylabel)
* перечисление [`SensitivityLabelAssignmentType`](/slides/python-net/ru/aspose.slides/sensitivitylabelassignmenttype)
* класс [`SensitivityLabelCollection`](/slides/python-net/ru/aspose.slides/sensitivitylabelcollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)