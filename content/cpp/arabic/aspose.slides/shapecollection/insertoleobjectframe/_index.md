---
title: InsertOleObjectFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 196
url: /ar/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الأساس الذي يتم عنده إدراج إطار كائن OLE. |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | معلومات بيانات OLE المدمجة ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### قيمة الإرجاع

[IOleObjectFrame](../../ioleobjectframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إدراج كائن OLE في الفهرس الثاني: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) طريقة

ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الأساس الذي يتم عنده إدراج إطار كائن OLE. |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| className | [System::String](../../../system/string/) | اسم الفئة لكائن OLE. |
| path | [System::String](../../../system/string/) | المسار إلى الملف المرتبط. |

### قيمة الإرجاع

إطار كائن OLE الذي تم إنشاؤه حديثًا.

## ملاحظات

يتم حفظ هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فإن الملف سيكون غير قابل للوصول عند فتح العرض التقديمي من دليل مختلف.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)