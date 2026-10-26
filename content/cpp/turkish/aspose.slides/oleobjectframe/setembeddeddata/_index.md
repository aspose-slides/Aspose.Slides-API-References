---
title: SetEmbeddedData()
second_title: Aspose.Slides için C++ API Referansı
description: OLE gömülü verileri hakkında bilgi ayarlar.
type: docs
weight: 248
url: /tr/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) yöntemi

OLE gömülü verileri hakkında bilgi ayarlar.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü veri [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Açıklamalar

Bu yöntem, nesnenin özelliklerini yeni verileri yansıtacak şekilde değiştirir ve IsObjectLink bayrağını false olarak ayarlar; bu, OLE nesnesinin gömülü olduğunu gösterir.



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
* Sınıf [OleObjectFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)