---
title: AddAutoShape()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإنشاء شكل تلقائي جديد بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 313
url: /ar/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) طريقة

يقوم بإنشاء شكل تلقائي جديد بالتنسيق الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) للشكـل التلقائي المراد إضافته. |
| x | **float** | الإحداثي السيني لإطار الشكل، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بوحدات النقاط. |
| width | **float** | العرض لإطار الشكل، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار الشكل، بوحدات النقاط. |

### قيمة الإرجاع

[IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) طريقة

يقوم بإنشاء شكل تلقائي جديد ويضيفه إلى نهاية مجموعة الأشكال، ويمكنه اختيارياً تهيئته باستخدام تنسيق القالب الافتراضي.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) للشكـل التلقائي المراد إضافته. |
| x | **float** | الإحداثي السيني لإطار الشكل، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بوحدات النقاط. |
| width | **float** | العرض لإطار الشكل، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار الشكل، بوحدات النقاط. |
| createFromTemplate | **bool** | True لتطبيق تنسيق القالب الافتراضي (نمط بسيط، نص متوسط، واسم غير فارغ) على الشكل الجديد؛ false لإنشاء الشكل بجميع الخصائص مضبوطة على القيم الافتراضية. |

### قيمة الإرجاع

[IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [IShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)