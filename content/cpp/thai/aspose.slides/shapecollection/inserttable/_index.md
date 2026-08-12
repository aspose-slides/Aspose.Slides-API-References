---
title: InsertTable()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ
type: docs
weight: 482
url: /th/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) เมธอด

Creates a new table and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรกตาราง. |
| x | **float** | พิกัดแกน x ของตารางหน่วยเป็นพอยต์. |
| y | **float** | พิกัดแกน y ของตารางหน่วยเป็นพอยต์. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาเรย์ของประเภท double ที่แสดงความกว้างของคอลัมน์ของตาราง, หน่วยเป็นพอยต์. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาเรย์ของประเภท double ที่แสดงความสูงของแถวของตาราง, หน่วยเป็นพอยต์. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [ITable](../../itable/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ITable](../../itable/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)