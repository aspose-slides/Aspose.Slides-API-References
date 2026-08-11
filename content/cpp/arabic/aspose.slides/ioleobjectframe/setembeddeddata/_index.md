---
title: SetEmbeddedData()
second_title: مرجع API Aspose.Slides للـ C++
description: يضبط معلومات حول بيانات OLE المضمنة.
type: docs
weight: 248
url: /ar/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

يضبط معلومات حول بيانات OLE المضمنة.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | بيانات مدمجة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## ملاحظات

تغيّر هذه الطريقة خصائص الكائن لتعكس البيانات الجديدة وتضبط علم IsObjectLink على false، مما يشير إلى أن كائن OLE مضمّن. 

يوضح المثال التالي كيفية تغيير بيانات OLE المضمنة ونوعها لكائن [IOleObjectFrame](../) الموجود 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## انظر أيضًا

* نوع تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* فئة [IOleObjectFrame](../)
* فضاء الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)