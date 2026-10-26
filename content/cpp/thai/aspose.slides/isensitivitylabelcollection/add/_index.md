---
title: Add()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน
type: docs
weight: 27
url: /th/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) เมธอด


เพิ่มป้ายความละเอียดที่ส่วนท้ายของคอลเลกชัน

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | หมายเลขประจำตัวของป้ายความละเอียด |
| siteId | [System::Guid](../../../system/guid/) | ตัวระบุไซต์ของ Azure Active Directory (Azure AD) |
| isEnabled | **bool** | แฟล็กบ่งชี้ว่าป้ายความละเอียดเปิดใช้งานหรือไม่ |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | วิธีการมอบหมายสำหรับป้ายความละเอียด |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) เมธอด


เพิ่ม [SensitivityLabel](../../sensitivitylabel/) ไปยังคอลเลกชัน

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | อ็อบเจ็กต์ [SensitivityLabel](../../sensitivitylabel/) ที่จะถูกเพิ่มที่ส่วนท้ายของคอลเลกชัน |

### ค่าที่ส่งกลับ

ดัชนีที่ [SensitivityLabel](../../sensitivitylabel/) ถูกเพิ่ม

## ดูเพิ่มเติม

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISensitivityLabel](../../isensitivitylabel/)
* คลาส [String](../../../system/string/)
* คลาส [Guid](../../../system/guid/)
* คลาส [ISensitivityLabelCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)