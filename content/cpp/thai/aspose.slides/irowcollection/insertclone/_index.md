---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกเข้าไปในตำแหน่งที่กำหนดในตาราง.
type: docs
weight: 27
url: /th/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) เมธอด

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกเข้าไปในตำแหน่งที่กำหนดในตาราง.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของแถวใหม่ |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) ที่ใช้เป็นแม่แบบ |
| withAttachedRows | **bool** | จริงเพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวแม่แบบด้วย |

### ค่าที่คืนกลับ

แถวที่แทรก

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IRow](../../irow/)
* คลาส [IRowCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)