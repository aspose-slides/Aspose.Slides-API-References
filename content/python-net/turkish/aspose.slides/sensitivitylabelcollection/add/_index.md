---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
SensitivityLabel'ı koleksiyona ekler.

### Döndürür

SensitivityLabel'ın eklendiği indeks.



```python
def add(self, label):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/tr/aspose.slides/isensitivitylabel) | Koleksiyonun sonuna eklenecek SensitivityLabel nesnesi. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Aynı Id'ye sahip duyarlılık etiketi zaten eklenmişse atılır. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/tr/aspose.slides/sensitivitylabelassignmenttype) |  |



### Bakınız
* sınıf [`ISensitivityLabel`](/slides/python-net/tr/aspose.slides/isensitivitylabel)
* enum [`SensitivityLabelAssignmentType`](/slides/python-net/tr/aspose.slides/sensitivitylabelassignmenttype)
* sınıf [`SensitivityLabelCollection`](/slides/python-net/tr/aspose.slides/sensitivitylabelcollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)