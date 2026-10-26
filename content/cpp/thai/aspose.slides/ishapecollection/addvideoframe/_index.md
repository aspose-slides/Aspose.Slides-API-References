---
title: AddVideoFrame()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง
type: docs
weight: 170
url: /th/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) เมธอด

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| y | **float** | พิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| width | **float** | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| fname | [System::String](../../../system/string/) | เส้นทางหรือชื่อไฟล์วิดีโอที่จะฝัง |

### ค่าที่ส่งกลับ

วัตถุที่สร้างใหม่ [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) เมธอด

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| y | **float** | พิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| width | **float** | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| height | **float** | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นพอยท์ |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) ที่จะฝังในเฟรมวิดีโอ |

### ค่าที่ส่งกลับ

วัตถุที่สร้างใหม่ [IVideoFrame](../../ivideoframe/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IVideoFrame](../../ivideoframe/)
* คลาส [String](../../../system/string/)
* คลาส [IShapeCollection](../)
* คลาส [IVideo](../../ivideo/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)