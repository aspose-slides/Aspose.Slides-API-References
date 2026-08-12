---
title: GetCell()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่
type: docs
weight: 27
url: /th/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) เมธอด

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงาน. |
| row | **int32_t** | แถว. |
| column | **int32_t** | คอลัมน์. |

### ค่าที่ส่งกลับ

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) เมธอด

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงาน. |
| row | **int32_t** | แถว. |
| column | **int32_t** | คอลัมน์. |

### ค่าที่ส่งกลับ

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) เมธอด

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงาน. |
| cellName | [System::String](../../../system/string/) | ชื่อของเซลล์. |

### ค่าที่ส่งกลับ

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) เมธอด

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงาน. |
| cellName | [System::String](../../../system/string/) | ชื่อของเซลล์. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า. |

### ค่าที่ส่งกลับ

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) เมธอด

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลแผนภูมิหรือหมวดหมู่

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงาน. |
| row | **int32_t** | แถว. |
| column | **int32_t** | คอลัมน์. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า. |

### ค่าที่ส่งกลับ

[Cell](../../../aspose.slides/cell/) object

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [ChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)