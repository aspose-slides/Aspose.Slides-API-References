---
title: SetEmbeddedData()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur informasi tentang data OLE yang disematkan.
type: docs
weight: 248
url: /id/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) metode

Mengatur informasi tentang data OLE yang disematkan.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Data yang disematkan [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Catatan

Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menunjukkan bahwa objek OLE disematkan.

Contoh berikut menunjukkan cara mengubah data OLE yang disematkan dan tipenya untuk objek [IOleObjectFrame](../) yang sudah ada.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Kelas [IOleObjectFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)