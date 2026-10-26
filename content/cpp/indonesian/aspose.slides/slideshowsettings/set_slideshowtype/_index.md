---
title: set_SlideShowType()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur tipe pertunjukan slide. Diwakili oleh nenek moyang SlideShowType berikut: BrowsedAtKiosk, PresentedBySpeaker dan BrowsedByIndividual"
type: docs
weight: 14
url: /id/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metode

Mengatur tipe pertunjukan slide. Diwakili oleh [SlideShowType](../../slideshowtype/) nenek moyang berikut: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) dan [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();

// untuk mengatur tipe "Browsed at a kiosk (layar penuh)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// untuk mengatur tipe "Browsed by individual (jendela)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// untuk mengatur tipe "Presented by a speaker (layar penuh)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [SlideShowType](../../slideshowtype/)
* Kelas [SlideShowSettings](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)