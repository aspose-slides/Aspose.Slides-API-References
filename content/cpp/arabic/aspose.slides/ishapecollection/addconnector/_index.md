---
title: AddConnector()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ شكلاً موصلاً جديدًا باستخدام تنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 378
url: /ar/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) طريقة

ينشئ شكلاً موصلاً جديداً باستخدام نمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بالشكل الموصل لإضافته. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) طريقة

ينشئ شكلاً موصلاً جديداً ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بالشكل الموصل لإنشائه. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | **bool** | صحيح لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ خطأ لإنشاء الموصل بقيم الخصائص الافتراضية. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)