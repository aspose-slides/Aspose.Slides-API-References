---
title: InsertConnector()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ شكل موصل جديدًا ويضيفه إلى مجموعة الأشكال في الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.
type: docs
weight: 391
url: /ar/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) طريقة

ينشئ شكل موصل جديدًا ويضيفه إلى مجموعة الأشكال في الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يتم عنده إدراج شكل الموصل. |
| shapeType | [ShapeType](../../shapetype/) | الـ[ShapeType](../../shapetype/) لشكل الموصل المراد إدراجه. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الجديد الذي تم إنشاؤه.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) طريقة

ينشئ شكل موصل جديدًا ويضيفه إلى مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يتم عنده إدراج شكل الموصل. |
| shapeType | [ShapeType](../../shapetype/) | الـ[ShapeType](../../shapetype/) لشكل الموصل المراد إدراجه. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | **bool** | True لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الجديد الذي تم إنشاؤه.

## انظر أيضًا

* تعداد [ShapeType](../../shapetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IConnector](../../iconnector/)
* فئة [IShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)