---
title: set_RootDirectoryClsid()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /id/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) metode

Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* Kelas [IPptOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)