---
title: AddSmartArt()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างแผนภาพ SmartArt และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.
type: docs
weight: 40
url: /th/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) เมธอด

สร้างแผนภาพ [SmartArt](../../../aspose.slides.smartart/) และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของเฟรมของแผนภาพ, หน่วยเป็นพ้อยต์ |
| y | **float** | พิกัด y ของเฟรมของแผนภาพ, หน่วยเป็นพ้อยต์ |
| width | **float** | ความกว้างของเฟรมของแผนภาพ, หน่วยเป็นพ้อยต์ |
| height | **float** | ความสูงของเฟรมของแผนภาพ, หน่วยเป็นพ้อยต์ |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | ประเภทการจัดวาง [SmartArt](../../../aspose.slides.smartart/) |

### ค่าที่คืน

[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) ที่สร้างใหม่

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## ดูเพิ่มเติม

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)