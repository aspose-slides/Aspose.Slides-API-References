---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกไว้ที่ส่วนล่างของตาราง.
type: docs
weight: 14
url: /th/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) เมธอด

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกไว้ที่ส่วนล่างของตาราง.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) ที่ใช้เป็นเทมเพลต. |
| withAttachedColumns | **bool** | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับแถวเทมเพลตด้วย. |

### ค่าที่คืนกลับ

คอลัมน์ที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IColumn](../../icolumn/)
* คลาส [IColumnCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)