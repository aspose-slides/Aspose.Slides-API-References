---
title: add method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Añade un SensitivityLabel a la colección.

### Devuelve

El índice en el que se añadió el SensitivityLabel.



```python
def add(self, label):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/es/aspose.slides/isensitivitylabel) | El objeto SensitivityLabel que se añadirá al final de la colección. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando la etiqueta de sensibilidad con el mismo Id ya ha sido añadida. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/es/aspose.slides/sensitivitylabelassignmenttype) |  |



### Ver también
* clase [`ISensitivityLabel`](/slides/python-net/es/aspose.slides/isensitivitylabel)
* enumeración [`SensitivityLabelAssignmentType`](/slides/python-net/es/aspose.slides/sensitivitylabelassignmenttype)
* clase [`SensitivityLabelCollection`](/slides/python-net/es/aspose.slides/sensitivitylabelcollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)