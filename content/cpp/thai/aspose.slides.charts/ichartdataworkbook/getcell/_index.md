---
title: GetCell()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ
type: docs
weight: 40
url: /th/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) เมธอด

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของเวิร์กชีต |
| row | **int32_t** | แถว |
| column | **int32_t** | คอลัมน์ |

### ค่าที่ส่งคืน

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) เมธอด

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีต |
| row | **int32_t** | แถว |
| column | **int32_t** | คอลัมน์ |

### ค่าที่ส่งคืน

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) เมธอด

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีต |
| cellName | [System::String](../../../system/string/) | ชื่อของเซลล์ |

### ค่าที่ส่งคืน

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) เมธอด

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีต |
| cellName | [System::String](../../../system/string/) | ชื่อของเซลล์ |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า |

### ค่าที่ส่งคืน

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) เมธอด

รับเซลล์ที่สามารถใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีต |
| row | **int32_t** | แถว |
| column | **int32_t** | คอลัมน์ |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า |

### ค่าที่ส่งคืน

[Cell](../../../aspose.slides/cell/) object

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [String](../../../system/string/)
* คลาส [IChartDataWorkbook](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)