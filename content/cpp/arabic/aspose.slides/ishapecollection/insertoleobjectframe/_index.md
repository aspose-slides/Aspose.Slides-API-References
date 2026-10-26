---
title: InsertOleObjectFrame()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 79
url: /ar/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

ينشئ إطار كائن OLE جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يُدرج عنده إطار كائن OLE. |
| x | **float** | الإحداثي السيني لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | معلومات البيانات المضمنة لـ OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### قيمة الإرجاع

العنصر الجديد [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) طريقة

ينشئ إطار كائن OLE جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري الذي يُدرج عنده إطار كائن OLE. |
| x | **float** | الإحداثي السيني لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| className | [System::String](../../../system/string/) | اسم الفئة لكائن OLE. |
| path | [System::String](../../../system/string/) | المسار إلى الملف المرتبط. |

### قيمة الإرجاع

العنصر الجديد [IOleObjectFrame](../../ioleobjectframe/).

## ملاحظات

يُخزن هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فإن الملف سيصبح غير قابل للوصول عند فتح العرض التقديمي من دليل مختلف.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IOleObjectFrame](../../ioleobjectframe/)
* فئة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* فئة [IShapeCollection](../)
* فئة [String](../../../system/string/)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)