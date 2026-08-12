---
title: AddContentPlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ.
type: docs
weight: 1
url: /th/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) เมธอด


เพิ่มรูปทรง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรง placeholder ใหม่. |
| y | **float** | พิกัด Y ของรูปทรง placeholder ใหม่. |
| width | **float** | ความกว้างของรูปทรง placeholder ใหม่. |
| height | **float** | ความสูงของรูปทรง placeholder ใหม่. |

### ค่ารีเทิร์น

สร้าง [IAutoShape](../../iautoshape/) ด้วย placeholder เนื้อหา.

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรง placeholder เนื้อหาไปยังสไลด์เค้าโครง. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## ดูเพิ่มเติม

* ชนิดกำหนดแบบ [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)