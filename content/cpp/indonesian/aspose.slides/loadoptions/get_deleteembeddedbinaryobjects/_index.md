---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang tersemat saat memuat presentasi.
type: docs
weight: 339
url: /id/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metode


Menentukan apakah [Aspose.Slides](../../) akan menghapus semua objek biner yang tersemat saat memuat presentasi.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Catatan


Jenis-jenis objek biner yang tersemat:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) data biner [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Baca **bool**. 

Default adalah **false**. 

Contoh berikut menunjukkan cara memuat presentasi tanpa objek biner yang tersemat apa pun. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Lihat Juga

* Kelas [LoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)