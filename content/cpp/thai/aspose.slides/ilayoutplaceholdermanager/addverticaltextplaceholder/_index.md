---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บเนื้อหาข้อความในแนวตั้ง
type: docs
weight: 40
url: /th/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บเนื้อหาข้อความในแนวตั้ง

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่ |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่ |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) ด้วย placeholder Text (Vertical)

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรง placeholder Text (Vertical) ลงในสไลด์เลเอาต์
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)