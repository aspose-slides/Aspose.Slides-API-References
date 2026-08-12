---
title: InsertTable()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ.
type: docs
weight: 443
url: /th/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้สำหรับแทรกตาราง |
| x | **float** | พิกัด x ของตาราง, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของตาราง, หน่วยเป็นพอยต์ |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาเรย์ของ double ที่แสดงความกว้างของคอลัมน์ของตาราง\u2019, หน่วยเป็นพอยต์ |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาเรย์ของ double ที่แสดงความสูงของแถวของตาราง\u2019, หน่วยเป็นพอยต์ |

### ค่าที่ส่งคืน

ออบเจกต์ที่สร้างใหม่ [ITable](../../itable/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ITable](../../itable/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)