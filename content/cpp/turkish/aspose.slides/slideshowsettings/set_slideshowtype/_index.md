---
title: set_SlideShowType()
second_title: Aspose.Slides C++ API Referansı
description: "Slayt gösterisi tipini ayarlar. Aşağıdaki SlideShowType atalar tarafından temsil edilir: BrowsedAtKiosk, PresentedBySpeaker ve BrowsedByIndividual"
type: docs
weight: 14
url: /tr/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) metodu


Slayt gösterisi tipini ayarlar. Aşağıdaki [SlideShowType](../../slideshowtype/) atalar tarafından temsil edilir: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) ve [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();

// "Kiosk'ta görüntülenen (tam ekran)" türünü ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Bireysel olarak görüntülenen (pencere)" türünü ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Bir konuşmacı tarafından sunulan (tam ekran)" türünü ayarlamak için
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [SlideShowType](../../slideshowtype/)
* Sınıf [SlideShowSettings](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)