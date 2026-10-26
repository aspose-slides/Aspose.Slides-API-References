---
title: AddSmartArt()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 79
url: /ar/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) طريقة

ينشئ مخطط [SmartArt](../../../aspose.slides.smartart/) ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي x لإطار المخطط، بالنقاط. |
| y | **float** | إحداثي y لإطار المخطط، بالنقاط. |
| width | **float** | عرض إطار المخطط، بالنقاط. |
| height | **float** | ارتفاع إطار المخطط، بالنقاط. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | نوع تخطيط [SmartArt](../../../aspose.slides.smartart/). |

### قيمة الإرجاع

ال[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) الذي تم إنشاؤه حديثًا.
## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## انظر أيضًا

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)