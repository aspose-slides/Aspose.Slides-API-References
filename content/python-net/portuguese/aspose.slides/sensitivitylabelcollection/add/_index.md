---
title: add method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Adiciona um SensitivityLabel à coleção.

### Retorno

O índice no qual o SensitivityLabel foi adicionado.



```python
def add(self, label):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/pt/aspose.slides/isensitivitylabel) | O objeto SensitivityLabel a ser adicionado ao final da coleção. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada quando o rótulo de sensibilidade com o mesmo Id já foi adicionado. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/pt/aspose.slides/sensitivitylabelassignmenttype) |  |



### Veja Também
* class [`ISensitivityLabel`](/slides/python-net/pt/aspose.slides/isensitivitylabel)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/pt/aspose.slides/sensitivitylabelassignmenttype)
* class [`SensitivityLabelCollection`](/slides/python-net/pt/aspose.slides/sensitivitylabelcollection)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)