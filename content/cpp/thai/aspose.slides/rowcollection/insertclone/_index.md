---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกลงในตำแหน่งที่กำหนดในตาราง.
type: docs
weight: 66
url: /th/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) เมธอด


สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกลงในตำแหน่งที่กำหนดในตาราง.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของแถวใหม่. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) ที่ใช้เป็นเทมเพลต. |
| withAttachedRows | **bool** | True เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวเทมเพลตด้วย. |

### ค่าที่คืน

แถวที่ถูกแทรก.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IRow](../../irow/)
* คลาส [RowCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)