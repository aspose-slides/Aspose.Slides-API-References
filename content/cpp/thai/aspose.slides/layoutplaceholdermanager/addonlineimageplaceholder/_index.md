---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides สำหรับ C++ – เอกสารอ้างอิง API
description: เพิ่มรูปทรงตัวแทนใหม่ไปยังสไลด์เลเอาต์เพื่อเก็บภาพออนไลน์.
type: docs
weight: 118
url: /th/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) method


เพิ่มรูปทรงตัวแทนที่ใหม่ไปยังสไลด์เลเอาต์เพื่อเก็บภาพออนไลน์.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | พิกัด X ของรูปทรงตัวแทนที่ใหม่ |
| y | **float** | พิกัด Y ของรูปทรงตัวแทนที่ใหม่ |
| width | **float** | ความกว้างของรูปทรงตัวแทนที่ใหม่ |
| height | **float** | ความสูงของรูปทรงตัวแทนที่ใหม่ |

### Return Value

สร้าง [IAutoShape](../../iautoshape/) พร้อมตัวแทนภาพออนไลน์.
## Remarks



ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปทรงตัวแทนภาพออนไลน์ไปยังสไลด์เลเอาต์ 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)