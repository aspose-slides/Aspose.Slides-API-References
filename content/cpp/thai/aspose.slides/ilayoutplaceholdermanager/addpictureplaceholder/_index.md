---
title: AddPicturePlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่ม placeholder shape ใหม่ไปยัง layout slide เพื่อเก็บรูปภาพ.
type: docs
weight: 53
url: /th/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) เมธอด

เพิ่ม placeholder shape ใหม่ไปยัง layout slide เพื่อเก็บรูปภาพ

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของ placeholder shape ใหม่ |
| y | **float** | พิกัด Y ของ placeholder shape ใหม่ |
| width | **float** | ความกว้างของ placeholder shape ใหม่ |
| height | **float** | ความสูงของ placeholder shape ใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder [Picture](../../picture/)

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่าง placeholder [Picture](../../picture/) ไปยัง layout slide
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)