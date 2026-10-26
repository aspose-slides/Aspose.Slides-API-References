---
title: get_SlideShowType()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan jenis pertunjukan slide. Diwakili oleh nenek moyang SlideShowType berikut: BrowsedAtKiosk, PresentedBySpeaker, dan BrowsedByIndividual"
type: docs
weight: 1
url: /id/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() metode


Mendapatkan jenis pertunjukan slide. Diwakili oleh [SlideShowType](../../slideshowtype/) nenek moyang berikut: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) dan [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>();

// untuk mengatur tipe "Browsed at a kiosk (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// untuk mengatur tipe "Browsed by individual (window)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// untuk mengatur tipe "Presented by a speaker (full screen)" type
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [SlideShowType](../../slideshowtype/)
* Kelas [SlideShowSettings](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)