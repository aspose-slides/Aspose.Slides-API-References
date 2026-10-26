---
title: InsertClone()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสำเนาของคอลัมน์เทมเพลตที่ระบุและแทรกลงในตำแหน่งที่กำหนดในตาราง.
type: docs
weight: 66
url: /th/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) เมธอด

สร้างสำเนาของคอลัมน์เทมเพลตที่ระบุและแทรกมันที่ตำแหน่งที่ระบุในตาราง.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของคอลัมน์ใหม่ |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) ซึ่งใช้เป็นเทมเพลต |
| withAttachedColumns | **bool** | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับคอลัมน์เทมเพลตด้วย |

### ค่าที่คืน

คอลัมน์ที่แทรก

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IColumn](../../icolumn/)
* คลาส [ColumnCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)