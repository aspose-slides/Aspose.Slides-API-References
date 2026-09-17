---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Añade una SensitivityLabel a la colección.

### Devuelve
El índice en el que se añadió la SensitivityLabel.



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
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada cuando la etiqueta de sensibilidad con el mismo Id ya ha sido añadida. |


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
* clase [`ISensitivityLabelCollection`](/slides/python-net/es/aspose.slides/isensitivitylabelcollection)
* enumeración [`SensitivityLabelAssignmentType`](/slides/python-net/es/aspose.slides/sensitivitylabelassignmenttype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)