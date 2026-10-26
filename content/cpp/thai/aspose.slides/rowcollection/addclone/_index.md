---
title: AddClone()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง.
type: docs
weight: 53
url: /th/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) เมธอด


สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) ที่ใช้เป็นแม่แบบ. |
| withAttachedRows | **bool** | True เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวแม่แบบด้วย. |

### ค่าที่คืนกลับ

แถวที่เพิ่ม

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)