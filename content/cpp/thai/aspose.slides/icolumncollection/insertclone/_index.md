---
title: InsertClone()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกไว้ที่ตำแหน่งที่ระบุในตาราง
type: docs
weight: 27
url: /th/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกไว้ที่ตำแหน่งที่ระบุในตาราง

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของคอลัมน์ใหม่ |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) ที่ใช้เป็นแม่แบบ |
| withAttachedColumns | **bool** | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับคอลัมน์แม่แบบด้วย |

### ค่าที่ส่งกลับ

คอลัมน์ที่แทรก

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IColumn](../../icolumn/)
* คลาส [IColumnCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)