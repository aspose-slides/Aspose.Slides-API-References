---
title: AddSmartArt()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างไดอะแกรม SmartArt แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชัน shape
type: docs
weight: 79
url: /th/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) เมธอด

สร้าง [SmartArt](../../../aspose.slides.smartart/) ไดอะแกรมและเพิ่มไปยังส่วนท้ายของคอลเลกชัน shape

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของกรอบไดอะแกรม, หน่วย points |
| y | **float** | พิกัด y ของกรอบไดอะแกรม, หน่วย points |
| width | **float** | ความกว้างของกรอบไดอะแกรม, หน่วย points |
| height | **float** | ความสูงของกรอบไดอะแกรม, หน่วย points |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) ประเภทการจัดวาง |

### ค่าที่ส่งกลับ

[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) ที่สร้างใหม่.

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## ดูเพิ่มเติม

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)