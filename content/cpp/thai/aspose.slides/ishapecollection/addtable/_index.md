---
title: AddTable()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตารางใหม่และเพิ่มเข้าไปที่ท้ายของคอลเลกชันรูปทรง
type: docs
weight: 430
url: /th/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

สร้างตารางใหม่และเพิ่มเข้าไปที่ท้ายของคอลเลกชันรูปทรง

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของตาราง หน่วยเป็นจุด |
| y | **float** | พิกัด y ของตาราง หน่วยเป็นจุด |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาร์เรย์ของค่า **double** ที่แสดงความกว้างของคอลัมน์ของตาราง หน่วยเป็นจุด |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาร์เรย์ของค่า **double** ที่แสดงความสูงของแถวของตาราง หน่วยเป็นจุด |

### Return Value

[ITable](../../itable/) ที่สร้างใหม่

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ITable](../../itable/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)