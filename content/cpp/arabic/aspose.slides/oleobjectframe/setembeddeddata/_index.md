---
title: SetEmbeddedData()
second_title: Aspose.Slides للغة C++ مرجع API
description: يضبط معلومات حول بيانات OLE المضمنة.
type: docs
weight: 248
url: /ar/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) طريقة

يضبط معلومات حول بيانات OLE المضمنة.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | البيانات المضمنة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## ملاحظات

هذه الطريقة تغير خصائص الكائن لتعكس البيانات الجديدة وتضبط علم IsObjectLink إلى false، مما يشير إلى أن كائن OLE مضمّن. 



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

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* فئة [OleObjectFrame](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)