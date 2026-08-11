---
title: AddOleObjectFrame()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 183
url: /ar/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

يقوم بإنشاء إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | معلومات عن بيانات OLE المضمنة ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### قيمة الإرجاع

الـ[IOleObjectFrame](../../ioleobjectframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

تظهر الأمثلة التالية كيفية إضافة إطارات كائن OLE إلى [Slides](../../) في PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// الوصول إلى الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);
// يحمّل ملف Excel إلى تدفق
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// ينشئ كائن بيانات للتضمين
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// يضيف شكل إطار كائن OLE
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//يكتب ملف PPTX إلى القرص
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) طريقة

يقوم بإنشاء إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| className | [System::String](../../../system/string/) | اسم الفئة لكائن OLE. |
| path | [System::String](../../../system/string/) | المسار إلى الملف المرتبط. |

### قيمة الإرجاع

الـ[IOleObjectFrame](../../ioleobjectframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يتم تخزين هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبى، سيكون الملف غير قابل للوصول عند فتح العرض التقديمي من دليل مختلف.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)