---
title: AddSmartArt()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار SmartArt ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.
type: docs
weight: 79
url: /fa/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) متد

یک نمودار [SmartArt](../../../aspose.slides.smartart/) ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x قاب نمودار\\u2019s، به نقطه. |
| y | **float** | مختصات y قاب نمودار\\u2019s، به نقطه. |
| width | **float** | عرض قاب نمودار\\u2019s، به نقطه. |
| height | **float** | ارتفاع قاب نمودار\\u2019s، به نقطه. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | نوع طرح [SmartArt](../../../aspose.slides.smartart/). |

### مقدار بازگشت

[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) جدید ایجاد شده.

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## موارد مرتبط

* enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* کلاس [ShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)