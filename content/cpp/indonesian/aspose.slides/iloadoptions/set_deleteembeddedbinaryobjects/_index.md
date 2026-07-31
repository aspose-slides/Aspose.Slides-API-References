---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat pemuatan presentasi.
type: docs
weight: 352
url: /id/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metode

Menentukan apakah [Aspose.Slides](../../) akan menghapus semua objek biner yang disematkan saat memuat presentasi.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Catatan

Jenis-jenis objek biner yang disematkan:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Tulis **bool**. 

Nilai default adalah **false**. 

Contoh berikut menunjukkan cara memuat presentasi tanpa objek biner yang disematkan apa pun. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Lihat Juga

* Kelas [ILoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)