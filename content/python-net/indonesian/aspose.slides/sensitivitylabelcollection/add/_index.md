---
title: add method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Menambahkan SensitivityLabel ke koleksi.

### Mengembalikan

Indeks tempat SensitivityLabel ditambahkan.



```python
def add(self, label):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/id/aspose.slides/isensitivitylabel) | Objek SensitivityLabel yang akan ditambahkan di akhir koleksi. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika label sensitivitas dengan Id yang sama sudah ditambahkan. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/id/aspose.slides/sensitivitylabelassignmenttype) |  |



### Lihat Juga
* kelas [`ISensitivityLabel`](/slides/python-net/id/aspose.slides/isensitivitylabel)
* enumerasi [`SensitivityLabelAssignmentType`](/slides/python-net/id/aspose.slides/sensitivitylabelassignmenttype)
* kelas [`SensitivityLabelCollection`](/slides/python-net/id/aspose.slides/sensitivitylabelcollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)