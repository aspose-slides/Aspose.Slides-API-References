---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API Referansı
description: Bağlı sunumun özelliklerini günceller.
type: docs
weight: 92
url: /tr/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metod

Bağlı sunumun özelliklerini günceller.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Belge özellikleri [IDocumentProperties](../../idocumentproperties/) |
## Açıklamalar



Bu örnek, [IPresentationInfo::UpdateDocumentProperties](./) metodunu çağırarak [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metodunun döndürdüğü belge özelliklerini nasıl güncelleyeceğinizi gösterir.
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDocumentProperties](../../idocumentproperties/)
* Sınıf [IPresentationInfo](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)