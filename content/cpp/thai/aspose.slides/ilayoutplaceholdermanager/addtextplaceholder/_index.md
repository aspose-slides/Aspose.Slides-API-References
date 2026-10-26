---
title: AddTextPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ.
type: docs
weight: 27
url: /th/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่ |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่ |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder ข้อความ
## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรง placeholder ข้อความลงในสไลด์เค้าโครง
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)