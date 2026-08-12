---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง.
type: docs
weight: 53
url: /th/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) เมธอด

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) ที่ใช้เป็นแม่แบบ |
| withAttachedColumns | **bool** | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับแถวแม่แบบด้วย |

### ค่าที่ส่งคืน

คอลัมน์ที่เพิ่ม

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IColumn](../../icolumn/)
* คลาส [ColumnCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)