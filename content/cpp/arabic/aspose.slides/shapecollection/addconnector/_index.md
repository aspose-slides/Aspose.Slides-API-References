---
title: AddConnector()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بإنشاء شكل موصل جديد مع تنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 417
url: /ar/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) طريقة

يقوم بإنشاء شكل موصل جديد مع تنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بشكل الموصل الذي سيتم إضافته. |
| x | **float** | إحداثي x لإطار الموصل، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار الموصل، بوحدات النقاط. |
| width | **float** | عرض إطار الموصل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدات النقاط. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.
## ملاحظات

يوضح المثال التالي كيفية إضافة موصل (موصل منحني) بين شكلين (بيضة ومستطيل) في PowerPoint [Presentation](../../presentation/). 
```cpp
// إنشاء كائن من فئة العرض التي تمثل ملف PPTX
auto input = System::MakeObject<Presentation>();

// الوصول إلى مجموعة الأشكال لشريحة محددة
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// إضافة شكل بيضاوي تلقائي
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// إضافة شكل مستطيل تلقائي
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// إضافة شكل موصل إلى مجموعة أشكال الشريحة
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// ربط الأشكال باستخدام الموصل
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// استدعاء reroute الذي يحدد أقصر مسار تلقائي بين الأشكال
connector->Reroute();

// حفظ العرض
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) طريقة

يقوم بإنشاء شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق القالب الافتراضي.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | ال[ShapeType](../../shapetype/) الخاص بشكل الموصل الذي سيتم إنشاؤه. |
| x | **float** | إحداثي x لإطار الموصل، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار الموصل، بوحدات النقاط. |
| width | **float** | عرض إطار الموصل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدات النقاط. |
| createFromTemplate | **bool** | True لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

### قيمة الإرجاع

ال[IConnector](../../iconnector/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IConnector](../../iconnector/)
* فئة [ShapeCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)