---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มรูปทรงตัวพิมพ์ตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความในแนวตั้ง.
type: docs
weight: 40
url: /th/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) เมธอด

เพิ่มรูปทรงตัวพิมพ์ตำแหน่งใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความในแนวตั้ง.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวพิมพ์ตำแหน่งใหม่. |
| y | **float** | พิกัด Y ของรูปทรงตัวพิมพ์ตำแหน่งใหม่. |
| width | **float** | ความกว้างของรูปทรงตัวพิมพ์ตำแหน่งใหม่. |
| height | **float** | ความสูงของรูปทรงตัวพิมพ์ตำแหน่งใหม่. |

### ค่าที่ส่งคืน

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวพิมพ์ตำแหน่งข้อความ (แนวตั้ง).

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรงตัวพิมพ์ตำแหน่งข้อความ (แนวตั้ง) ลงในสไลด์เค้าโครง. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)