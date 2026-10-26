---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mendapatkan mode di mana slide ditempatkan pada halaman saat mengekspor presentasi ISlidesLayoutOptions.
type: docs
weight: 157
url: /id/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() method


Mendapatkan mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Kelas [IHtml5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)