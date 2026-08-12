---
title: AddTablePlaceholder()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: เพิ่มรูป placeholder ใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บตาราง.
type: docs
weight: 79
url: /th/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) เมธอด


เพิ่มรูป placeholder ใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บตาราง.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | **float** | ค่าพิกัด X ของรูป placeholder ใหม่. |
| y | **float** | ค่าพิกัด Y ของรูป placeholder ใหม่. |
| width | **float** | ความกว้างของรูป placeholder ใหม่. |
| height | **float** | ความสูงของรูป placeholder ใหม่. |

### ค่าที่คืน

สร้าง [IAutoShape](../../iautoshape/) ด้วย placeholder [Table](../../table/).

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูป placeholder [Table](../../table/) ลงในสไลด์เลย์เอาต์. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)