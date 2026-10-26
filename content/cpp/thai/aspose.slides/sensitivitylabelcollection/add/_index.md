---
title: Add()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) เมธอด

เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | ไอดีของป้ายความละเอียด |
| siteId | [System::Guid](../../../system/guid/) | ตัวระบุไซต์ของ Azure Active Directory (Azure AD) |
| isEnabled | **bool** | แฟล็กบ่งบอกว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่ |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | วิธีการมอบหมายสำหรับป้ายความละเอียด |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) เมธอด

เพิ่ม [SensitivityLabel](../../sensitivitylabel/) ไปยังคอลเลกชัน

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | อ็อบเจ็กต์ [SensitivityLabel](../../sensitivitylabel/) ที่จะถูกเพิ่มที่ส่วนท้ายของคอลเลกชัน |

### ค่าที่คืน

ดัชนีที่ [SensitivityLabel](../../sensitivitylabel/) ถูกเพิ่ม

## ดูเพิ่มเติม

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISensitivityLabel](../../isensitivitylabel/)
* คลาส [String](../../../system/string/)
* คลาส [Guid](../../../system/guid/)
* คลาส [SensitivityLabelCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)