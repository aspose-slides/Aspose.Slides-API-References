---
title: AddMediaPlaceholder()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มรูปทรงตัวเติมใหม่ไปยังสไลด์เลย์เอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ.
type: docs
weight: 105
url: /th/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรงตัวเติมใหม่ไปยังสไลด์เลย์เอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | ค่าพิกัด X ของรูปทรงตัวเติมใหม่ |
| y | **float** | ค่าพิกัด Y ของรูปทรงตัวเติมใหม่ |
| width | **float** | ความกว้างของรูปทรงตัวเติมใหม่ |
| height | **float** | ความสูงของรูปทรงตัวเติมใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวเติมสื่อ.

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรงตัวเติมสื่อไปยังสไลด์เลย์เอาต์
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)