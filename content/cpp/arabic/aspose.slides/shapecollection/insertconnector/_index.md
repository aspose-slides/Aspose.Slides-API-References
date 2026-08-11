---
title: InsertConnector()
second_title: Aspose.Slides لمرجع API C++
description: يقوم بإنشاء شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.
type: docs
weight: 430
url: /ar/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) الطريقة

يقوم بإنشاء شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج شكل الموصل. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) الخاص بشكل الموصل المراد إدراجه. |
| x | **float** | الإحداثي السيني لإطار الموصل، بوحدة النقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بوحدة النقاط. |
| width | **float** | عرض إطار الموصل، بوحدة النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدة النقاط. |

### قيمة الإرجاع

الـ[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) الطريقة

يقوم بإنشاء شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج شكل الموصل. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) الخاص بشكل الموصل المراد إدراجه. |
| x | **float** | الإحداثي السيني لإطار الموصل، بوحدة النقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بوحدة النقاط. |
| width | **float** | عرض إطار الموصل، بوحدة النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدة النقاط. |
| createFromTemplate | **bool** | صحيح لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ خطأ لإنشاء الموصل بقيم الخصائص الافتراضية. |

### قيمة الإرجاع

الـ[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.

## انظر أيضاً

* تعداد [ShapeType](../../shapetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صنف [IConnector](../../iconnector/)
* صنف [ShapeCollection](../)
* فضاء اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)