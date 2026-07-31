---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat memuat presentasi.
type: docs
weight: 352
url: /id/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metode

Menentukan apakah [Aspose.Slides](../../) akan menghapus semua objek biner tersemat saat memuat presentasi.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Catatan

Jenis-jenis objek biner tersemat:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object data tersemat [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) data biner [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Tulis **bool**.

Nilai default **false**.

Contoh berikut menunjukkan cara memuat presentasi tanpa objek biner tersemat apapun.
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