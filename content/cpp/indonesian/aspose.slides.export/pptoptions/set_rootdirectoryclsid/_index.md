---
title: set_RootDirectoryClsid()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori akar. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /id/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) method


Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori akar. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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
* Library [Aspose.Slides](../../../)