---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
เพิ่ม SensitivityLabel ไปยังคอลเลกชัน

### Returns
คืนค่าอินดексที่เพิ่ม SensitivityLabel เข้าไป

```python
def add(self, label):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/th/aspose.slides/isensitivitylabel) | อ็อบเจ็กต์ SensitivityLabel ที่จะถูกเพิ่มที่ส่วนท้ายของคอลเลกชัน |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อยกเว้นเมื่อมีการเพิ่ม sensitivity label ที่มี Id เดียวกันแล้ว |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}}

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

### See Also
* class [`ISensitivityLabel`](/slides/python-net/th/aspose.slides/isensitivitylabel)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/th/aspose.slides/sensitivitylabelassignmenttype)
* class [`SensitivityLabelCollection`](/slides/python-net/th/aspose.slides/sensitivitylabelcollection)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)