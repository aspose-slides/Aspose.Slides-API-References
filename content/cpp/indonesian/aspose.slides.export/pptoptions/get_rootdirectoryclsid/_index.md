---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM dari aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /id/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() metode


Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM dari aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Lihat Juga

* Kelas [Guid](../../../system/guid/)
* Kelas [PptOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)