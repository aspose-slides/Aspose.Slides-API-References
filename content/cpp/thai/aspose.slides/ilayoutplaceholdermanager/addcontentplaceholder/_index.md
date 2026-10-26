---
title: AddContentPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เลเอาท์เพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ.
type: docs
weight: 1
url: /th/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เลเอาท์เพื่อจัดเก็บเนื้อหา เช่น ภาพ ตาราง สื่อ หรือข้อความ.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | **float** | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | **float** | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | **float** | ความสูงของรูปแบบ placeholder ใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) ด้วย placeholder Content.

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปแบบ placeholder Content ลงในสไลด์เลเอาท์.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)