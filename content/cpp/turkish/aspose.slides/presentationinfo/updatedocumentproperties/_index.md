---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API Referansı
description: Bağlı sunumun özelliklerini günceller.
type: docs
weight: 92
url: /tr/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metod

Bağlı sunumun özelliklerini günceller.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Açıklamalar

Bu örnek, [PresentationInfo::UpdateDocumentProperties](./) metodunu çağırarak, [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) metodunun çağrısı ile döndürülen belge özelliklerini nasıl güncelleyeceğinizi gösterir.

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDocumentProperties](../../idocumentproperties/)
* Sınıf [PresentationInfo](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)