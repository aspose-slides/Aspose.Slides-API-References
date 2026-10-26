---
title: get_DefaultDelay()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de standaardvertragingstijd op [ms]. Deze waarde wordt gebruikt als de ISlideShowTransition::set_AdvanceAfterTime() methode niet is aangeroepen. De standaardwaarde is 1000."
type: docs
weight: 79
url: /nl/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() methode


Haalt de standaard vertragingstijd op [ms]. Deze waarde wordt gebruikt als de [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) methode niet is aangeroepen. De standaardwaarde is 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Zie ook

* Klasse [GifOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)