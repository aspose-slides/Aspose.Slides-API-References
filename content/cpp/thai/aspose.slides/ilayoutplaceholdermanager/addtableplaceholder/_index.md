---
title: AddTablePlaceholder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บตาราง.
type: docs
weight: 79
url: /th/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) เมธอด

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เลเอาต์เพื่อเก็บตาราง.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปร่าง placeholder ใหม่. |
| y | **float** | พิกัด Y ของรูปร่าง placeholder ใหม่. |
| width | **float** | ความกว้างของรูปร่าง placeholder ใหม่. |
| height | **float** | ความสูงของรูปร่าง placeholder ใหม่. |

### Return Value

สร้าง [IAutoShape](../../iautoshape/) ด้วย placeholder [Table](../../table/).

## Remarks

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปร่าง placeholder [Table](../../table/) ไปยังสไลด์เลเอาต์. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)