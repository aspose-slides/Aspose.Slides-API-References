---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API Referansı
description: OLE gömülü verileri hakkında bilgileri ayarlar.
type: docs
weight: 248
url: /tr/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metod


OLE gömülü veriler hakkında bilgileri ayarlar.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü veri [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Açıklamalar


Bu metod, nesnenin özelliklerini yeni veriyi yansıtacak şekilde değiştirir ve IsObjectLink bayrağını false olarak ayarlar; bu, OLE nesnesinin gömülü olduğunu gösterir. 


Aşağıdaki örnek, mevcut [IOleObjectFrame](../) nesnesi için OLE gömülü verisini ve tipini nasıl değiştireceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Sınıf [IOleObjectFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)