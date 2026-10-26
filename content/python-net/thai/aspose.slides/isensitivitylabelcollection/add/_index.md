---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
เพิ่ม SensitivityLabel ลงในคอลเลกชัน

### ค่าที่ส่งกลับ

ดัชนีที่ SensitivityLabel ถูกเพิ่ม



```python
def add(self, label):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/th/aspose.slides/isensitivitylabel) | วัตถุ SensitivityLabel ที่จะเพิ่มที่ส่วนท้ายของคอลเลกชัน |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะถูกโยนเมื่อ sensitivity label ที่มี Id เดียวกันได้ถูกเพิ่มไปแล้ว |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/th/aspose.slides/sensitivitylabelassignmenttype) |  |



### ดูเพิ่มเติม
* คลาส [`ISensitivityLabel`](/slides/python-net/th/aspose.slides/isensitivitylabel)
* คลาส [`ISensitivityLabelCollection`](/slides/python-net/th/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/th/aspose.slides/sensitivitylabelassignmenttype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)