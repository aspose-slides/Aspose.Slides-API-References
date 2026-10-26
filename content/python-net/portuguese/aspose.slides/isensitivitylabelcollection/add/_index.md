---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Adiciona um SensitivityLabel à coleção.

### Retorna

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
* classe [`ISensitivityLabel`](/slides/python-net/pt/aspose.slides/isensitivitylabel)
* classe [`ISensitivityLabelCollection`](/slides/python-net/pt/aspose.slides/isensitivitylabelcollection)
* enumeração [`SensitivityLabelAssignmentType`](/slides/python-net/pt/aspose.slides/sensitivitylabelassignmenttype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)