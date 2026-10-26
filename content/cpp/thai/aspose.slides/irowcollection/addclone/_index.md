---
title: AddClone()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ส่วนล่างของตาราง.
type: docs
weight: 14
url: /th/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) เมธอด


สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ส่วนล่างของตาราง

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) ซึ่งใช้เป็นแม่แบบ. |
| withAttachedRows | **bool** | True เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวแม่แบบด้วย. |

### ค่าที่ส่งกลับ

แถวที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)