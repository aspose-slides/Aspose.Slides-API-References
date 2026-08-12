---
title: AddChartPlaceholder()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มรูปร่าง placeholder ใหม่ไปยังสไลด์เลเอาต์เพื่อเก็บแผนภูมิ.
type: docs
weight: 66
url: /th/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) เมธอด


เพิ่มรูปร่าง placeholder ใหม่ไปยังสไลด์เลเอาต์เพื่อเก็บแผนภูมิ.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปร่าง placeholder ใหม่. |
| y | **float** | พิกัด Y ของรูปร่าง placeholder ใหม่. |
| width | **float** | ความกว้างของรูปร่าง placeholder ใหม่. |
| height | **float** | ความสูงของรูปร่าง placeholder ใหม่. |

### ค่าที่คืนกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมกับ placeholder แผนภูมิ.

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่าง placeholder แผนภูมิไปยังสไลด์เลเอาต์. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [ILayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)