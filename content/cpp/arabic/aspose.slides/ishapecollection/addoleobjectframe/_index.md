---
title: AddOleObjectFrame()
second_title: مرجع API Aspose.Slides للـ C++
description: يُنشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 66
url: /ar/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار OLE الجديد، بالنقاط. |
| width | **float** | العرض لإطار OLE الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار OLE الجديد، بالنقاط. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | معلومات بيانات OLE المضمنة ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### قيمة الإرجاع

الكائن [IOleObjectFrame](../../ioleobjectframe/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) طريقة

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار OLE الجديد، بالنقاط. |
| width | **float** | العرض لإطار OLE الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار OLE الجديد، بالنقاط. |
| className | [System::String](../../../system/string/) | اسم الفئة لكائن OLE. |
| path | [System::String](../../../system/string/) | المسار إلى الملف المرتبط. |

### قيمة الإرجاع

الكائن [IOleObjectFrame](../../ioleobjectframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يتم تخزين هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فإن الملف سيصبح غير قابل للوصول عند فتح العرض التقديمي من دليل مختلف.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IOleObjectFrame](../../ioleobjectframe/)
* فئة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* فئة [IShapeCollection](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)