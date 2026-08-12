---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์
type: docs
weight: 118
url: /th/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่ |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่ |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่ |

### ค่าที่คืน

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder ภาพออนไลน์

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรง placeholder ภาพออนไลน์ไปยังสไลด์เค้าโครง 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)