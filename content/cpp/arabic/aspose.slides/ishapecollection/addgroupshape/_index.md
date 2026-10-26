---
title: AddGroupShape()
second_title: Aspose.Slides لمرجع API لـ C++
description: ينشئ شكل مجموعة فارغًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه.
type: docs
weight: 352
url: /ar/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() طريقة

ينشئ شكل مجموعة فارغًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### قيمة الإرجاع

ال[IGroupShape](../../igroupshape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) طريقة

ينشئ شكل مجموعة جديدًا، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) التي تحتوي على محتوى متجه للتحويل إلى أشكال. |
| x | **float** | إحداثي x لإطار المجموعة، بالنقاط. |
| y | **float** | إحداثي y لإطار المجموعة، بالنقاط. |
| width | **float** | عرض إطار المجموعة، بالنقاط. |
| height | **float** | ارتفاع إطار المجموعة، بالنقاط. |

### قيمة الإرجاع

ال[IGroupShape](../../igroupshape/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IGroupShape](../../igroupshape/)
* فئة [IShapeCollection](../)
* فئة [ISvgImage](../../isvgimage/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)