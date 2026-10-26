---
title: AddSmartArt()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 40
url: /ar/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) طريقة

ينشئ مخطط [SmartArt](../../../aspose.slides.smartart/) ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | الإحداثي السيني لإطار المخطط، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار المخطط، بالنقاط. |
| width | **float** | عرض إطار المخطط، بالنقاط. |
| height | **float** | ارتفاع إطار المخطط، بالنقاط. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | نوع التخطيط [SmartArt](../../../aspose.slides.smartart/). |

### قيمة الإرجاع

الـ[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) الذي تم إنشاؤه حديثًا.

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
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)