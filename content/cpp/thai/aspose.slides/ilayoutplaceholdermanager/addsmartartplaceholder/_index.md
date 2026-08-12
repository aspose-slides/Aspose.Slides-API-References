---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ SmartArt.
type: docs
weight: 92
url: /th/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method

เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ [SmartArt](../../../aspose.slides.smartart/) diagram.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่ |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่ |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder [SmartArt](../../../aspose.slides.smartart/).

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรง placeholder [SmartArt](../../../aspose.slides.smartart/) ลงในสไลด์เค้าโครง. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)