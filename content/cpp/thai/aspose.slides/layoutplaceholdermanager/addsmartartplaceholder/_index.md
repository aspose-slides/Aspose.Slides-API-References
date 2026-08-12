---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปทรงตัวเติมใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ SmartArt.
type: docs
weight: 92
url: /th/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรงตัวเติมใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวเติมใหม่. |
| y | **float** | พิกัด Y ของรูปทรงตัวเติมใหม่. |
| width | **float** | ความกว้างของรูปทรงตัวเติมใหม่. |
| height | **float** | ความสูงของรูปทรงตัวเติมใหม่. |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) ด้วยตัวเติม [SmartArt](../../../aspose.slides.smartart/).

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรงตัวเติม [SmartArt](../../../aspose.slides.smartart/) ลงในสไลด์เค้าโครง.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)