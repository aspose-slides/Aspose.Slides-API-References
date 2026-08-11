---
title: AddAutoShape()
second_title: Aspose.Slides - مرجع API للغة C++
description: ينشئ شكلاً تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 352
url: /ar/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) طريقة

يُنشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بالشكل التلقائي المراد إضافته. |
| x | **float** | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |

### قيمة الإرجاع

العنصر [IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) طريقة

يُنشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بالشكل التلقائي المراد إضافته. |
| x | **float** | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | **bool** | صحيح لتطبيق نمط القالب الافتراضي (نمط بسيط، نص مركزي، واسم غير فارغ) على الشكل الجديد؛ خاطئ لإنشاء الشكل مع تعيين جميع الخصائص إلى قيمها الافتراضية. |

### قيمة الإرجاع

العنصر [IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)