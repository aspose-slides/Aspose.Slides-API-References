---
title: AddTextPlaceholder()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มรูปทรงตัวบรรจุใหม่ลงในสไลด์เลเอาท์เพื่อเก็บเนื้อหาแบบข้อความ.
type: docs
weight: 27
url: /th/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรงตัวบรรจุข้อความใหม่ลงในสไลด์เลเอาท์เพื่อเก็บเนื้อหาแบบข้อความ.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวบรรจุใหม่ |
| y | **float** | พิกัด Y ของรูปทรงตัวบรรจุใหม่ |
| width | **float** | ความกว้างของรูปทรงตัวบรรจุใหม่ |
| height | **float** | ความสูงของรูปทรงตัวบรรจุใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวบรรจุ Text.

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรงตัวบรรจุ Text ลงในสไลด์เลเอาท์. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)