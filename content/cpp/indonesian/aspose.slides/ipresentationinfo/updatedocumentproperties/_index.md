---
title: UpdateDocumentProperties()
second_title: Referensi API Aspose.Slides untuk C++
description: Memperbarui properti presentasi yang terikat.
type: docs
weight: 92
url: /id/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) metode


Memperbarui properti presentasi yang terikat.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Properti dokumen [IDocumentProperties](../../idocumentproperties/) |
## Catatan



Contoh ini menunjukkan cara memanggil metode [IPresentationInfo::UpdateDocumentProperties](./) untuk memperbarui properti dokumen yang dikembalikan oleh pemanggilan metode [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
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
* Kelas [IDocumentProperties](../../idocumentproperties/)
* Kelas [IPresentationInfo](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)