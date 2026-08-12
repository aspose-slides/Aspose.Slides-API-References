---
title: InsertChart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างแผนภูมิใหม่ กำหนดค่าเริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์ แล้วแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) เมธอด

สร้างแผนภูมิใหม่, กำหนดค่าเริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, แล้วแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่จะสร้าง. |
| x | **float** | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| index | **int32_t** | ดัชนีเริ่มที่ศูนย์ที่จะแทรกแผนภูมิใหม่ลงในคอลเลกชันรูปร่าง. |

### ค่าที่คืนกลับ

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) เมธอด

สร้างแผนภูมิใหม่, กำหนดค่าเริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, แล้วแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่จะสร้าง. |
| x | **float** | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| y | **float** | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| width | **float** | ความกว้างของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| height | **float** | ความสูงของแผนภูมิใหม่, หน่วยเป็นพอยต์. |
| index | **int32_t** | ดัชนีเริ่มที่ศูนย์ที่จะแทรกแผนภูมิใหม่ลงในคอลเลกชันรูปร่าง. |
| initWithSample | **bool** | True เพื่อกำหนดค่าเริ่มต้นของแผนภูมิใหม่ด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์; false เพื่อสร้างแผนภูมิที่ไม่มีซีรีส์และมีการตั้งค่าเพียงขั้นต่ำ ซึ่งทำให้การสร้างเร็วขึ้น. |

### ค่าที่คืนกลับ

The newly created [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ดูเพิ่มเติม

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)