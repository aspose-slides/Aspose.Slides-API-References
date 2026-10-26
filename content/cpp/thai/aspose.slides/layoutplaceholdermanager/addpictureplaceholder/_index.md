---
title: AddPicturePlaceholder()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มรูปทรงตัวแทนใหม่ในสไลด์เค้าโครงเพื่อเก็บรูปภาพ.
type: docs
weight: 53
url: /th/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) เมธอด


เพิ่มรูปทรงตัวแทนใหม่ในสไลด์เค้าโครงเพื่อเก็บรูปภาพ

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวแทนใหม่ |
| y | **float** | พิกัด Y ของรูปทรงตัวแทนใหม่ |
| width | **float** | ความกว้างของรูปทรงตัวแทนใหม่ |
| height | **float** | ความสูงของรูปทรงตัวแทนใหม่ |

### ค่าที่ส่งกลับ

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวแทน [Picture](../../picture/) placeholder.

## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปทรงตัวแทน [Picture](../../picture/) ไปยังสไลด์เค้าโครง 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IAutoShape](../../iautoshape/)
* คลาส [LayoutPlaceholderManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)