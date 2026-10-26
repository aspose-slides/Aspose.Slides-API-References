---
title: UpdateDocumentProperties()
second_title: Aspose.Slides untuk Referensi API C++
description: Memperbarui properti presentasi yang terikat.
type: docs
weight: 92
url: /id/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metode


Memperbarui properti presentasi yang terikat.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Catatan


Contoh ini menunjukkan cara memanggil metode [PresentationInfo::UpdateDocumentProperties](./) untuk memperbarui properti dokumen yang dikembalikan oleh pemanggilan metode [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDocumentProperties](../../idocumentproperties/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)