---
title: AddVideoFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 209
url: /th/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) เมธอด

สร้างเฟรมวีดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| y | **float** | พิกัด y ของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| width | **float** | ความกว้างของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| height | **float** | ความสูงของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| fname | [System::String](../../../system/string/) | พาธหรือชื่อของไฟล์วีดีโอที่จะแนบ. |

### ค่าที่ส่งกลับ

[IVideoFrame](../../ivideoframe/) ที่สร้างใหม่.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) เมธอด

สร้างเฟรมวีดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| y | **float** | พิกัด y ของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| width | **float** | ความกว้างของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| height | **float** | ความสูงของเฟรมวีดีโอใหม่ หน่วยเป็นพอยท์. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) ที่จะแนบในเฟรมวีดีโอ. |

### ค่าที่ส่งกลับ

[IVideoFrame](../../ivideoframe/) ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IVideoFrame](../../ivideoframe/)
* คลาส [String](../../../system/string/)
* คลาส [ShapeCollection](../)
* คลาส [IVideo](../../ivideo/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)