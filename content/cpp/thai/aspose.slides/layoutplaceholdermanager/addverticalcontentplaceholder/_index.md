---
title: AddVerticalContentPlaceholder()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มรูปแบบตัวแทนใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง
type: docs
weight: 14
url: /th/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปแบบตัวแทนใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปแบบตัวแทนใหม่ |
| y | **float** | พิกัด Y ของรูปแบบตัวแทนใหม่ |
| width | **float** | ความกว้างของรูปแบบตัวแทนใหม่ |
| height | **float** | ความสูงของรูปแบบตัวแทนใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวแทนเนื้อหา (แนวตั้ง)

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปแบบตัวแทนเนื้อหา (แนวตั้ง) ลงในสไลด์เค้าโครง
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)