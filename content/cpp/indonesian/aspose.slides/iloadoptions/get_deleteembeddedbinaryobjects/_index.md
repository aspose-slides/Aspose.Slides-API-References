---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat memuat presentasi.
type: docs
weight: 339
url: /id/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() metode

Menentukan apakah [Aspose.Slides](../../) akan menghapus semua objek biner yang disematkan saat memuat presentasi.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Catatan

Jenis-jenis objek biner yang disematkan:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Baca **bool**. 

Default adalah **false**. 

Contoh berikut menunjukkan cara memuat presentasi tanpa objek biner yang disematkan apa pun. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Lihat Juga

* Kelas [ILoadOptions](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)