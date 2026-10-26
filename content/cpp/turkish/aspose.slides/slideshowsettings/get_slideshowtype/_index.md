---
title: get_SlideShowType()
second_title: Aspose.Slides for C++ API Referansı
description: "Slayt gösterisi türünü alır. Aşağıdaki SlideShowType üst nesneleriyle temsil edilir: BrowsedAtKiosk, PresentedBySpeaker ve BrowsedByIndividual"
type: docs
weight: 1
url: /tr/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() yöntemi


Slayt gösterisi türünü alır. Aşağıdaki [SlideShowType](../../slideshowtype/) üst nesnelerle temsil edilir: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) ve [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();

// "Kiosk'ta gözatılan (tam ekran)" tipini ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Bireysel olarak gözatılan (pencere)" tipini ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Sunucu tarafından sunulan (tam ekran)" tipini ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [SlideShowType](../../slideshowtype/)
* Sınıf [SlideShowSettings](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)