---
title: AddMediaPlaceholder()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ
type: docs
weight: 105
url: /th/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่ |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่ |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่ |

### ค่าที่คืน

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder สื่อ

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรง Media placeholder ลงในสไลด์เลเอาต์ 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)