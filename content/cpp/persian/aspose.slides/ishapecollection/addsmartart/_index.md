---
title: AddSmartArt()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار SmartArt ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.
type: docs
weight: 40
url: /fa/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method

یک نمودار [SmartArt](../../../aspose.slides.smartart/) ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | مختصات x فریم نمودار، به واحد نقطه. |
| y | **float** | مختصات y فریم نمودار، به واحد نقطه. |
| width | **float** | عرض فریم نمودار، به واحد نقطه. |
| height | **float** | ارتفاع فریم نمودار، به واحد نقطه. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | The [SmartArt](../../../aspose.slides.smartart/) layout type. |

### مقدار بازگشت

‏[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) تازه ایجاد شده.

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## مراجع

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)