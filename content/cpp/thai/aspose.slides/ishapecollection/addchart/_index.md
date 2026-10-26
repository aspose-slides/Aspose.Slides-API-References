---
title: AddChart()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 27
url: /th/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) เมธอด

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่จะเพิ่ม |
| x | **float** | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์ |
| width | **float** | ความกว้างของแผนภูมิ, หน่วยเป็นพ้อยต์ |
| height | **float** | ความสูงของแผนภูมิ, หน่วยเป็นพ้อยต์ |

### ค่าที่ส่งคืน

อ็อบเจกต์ [Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) เมธอด

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่จะเพิ่ม |
| x | **float** | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นพ้อยต์ |
| width | **float** | ความกว้างของแผนภูมิ, หน่วยเป็นพ้อยต์ |
| height | **float** | ความสูงของแผนภูมิ, หน่วยเป็นพ้อยต์ |
| initWithSample | **bool** | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลชุดตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิที่ไม่มีชุดข้อมูลและมีการตั้งค่าขั้นต่ำเท่านั้น, ซึ่งทำให้การสร้างเร็วขึ้น |

### ค่าที่ส่งคืน

อ็อบเจกต์ [Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)