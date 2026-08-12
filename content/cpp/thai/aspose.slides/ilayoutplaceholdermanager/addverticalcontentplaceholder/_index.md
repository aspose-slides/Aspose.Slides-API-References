---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มรูปแบบตัวแทนตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น ภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง
type: docs
weight: 14
url: /th/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปร่างตัวแสดงตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปร่างตัวแสดงตำแหน่งใหม่ |
| y | **float** | พิกัด Y ของรูปร่างตัวแสดงตำแหน่งใหม่ |
| width | **float** | ความกว้างของรูปร่างตัวแสดงตำแหน่งใหม่ |
| height | **float** | ความสูงของรูปร่างตัวแสดงตำแหน่งใหม่ |

### ค่าที่ส่งกลับ

Created [IAutoShape](../../iautoshape/) with a Content (Vertical) placeholder.

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวแสดงตำแหน่งเนื้อหา (แนวตั้ง) ลงในสไลด์เค้าโครง. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)