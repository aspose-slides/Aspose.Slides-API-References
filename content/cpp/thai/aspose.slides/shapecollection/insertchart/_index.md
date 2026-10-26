---
title: InsertChart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันของรูปร่างตามดัชนีที่ระบุ.
type: docs
weight: 92
url: /th/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) เมธอด

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันของรูปร่างตามดัชนีที่ระบุ.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่ต้องการสร้าง. |
| x | **float** | ค่าพิกัด x ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| y | **float** | ค่าพิกัด y ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| width | **float** | ความกว้างของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| height | **float** | ความสูงของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรกแผนภูมิใหม่ในคอลเลกชันของรูปร่าง. |

### ค่าที่คืนกลับ

[Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) เมธอด

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันของรูปร่างตามดัชนีที่ระบุ.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่ต้องการสร้าง. |
| x | **float** | ค่าพิกัด x ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| y | **float** | ค่าพิกัด y ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| width | **float** | ความกว้างของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| height | **float** | ความสูงของแผนภูมิใหม่, หน่วยเป็นพ้อยต์. |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรกแผนภูมิใหม่ในคอลเลกชันของรูปร่าง. |
| initWithSample | **bool** | เป็น true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า; เป็น false เพื่อสร้างแผนภูมิโดยไม่มีซีรีส์และมีการตั้งค่าน้อยที่สุด ซึ่งทำให้การสร้างเร็วขึ้น. |

### ค่าที่คืนกลับ

[Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)