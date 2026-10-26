---
title: set_DefaultDelay()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de standaardvertragingstijd in [ms]. Deze waarde wordt gebruikt als de ISlideShowTransition::set_AdvanceAfterTime() methode niet werd aangeroepen. De standaardwaarde is 1000."
type: docs
weight: 92
url: /nl/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) methode


Stelt de standaardvertragingstijd in [ms]. Deze waarde wordt gebruikt indien de [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) methode niet werd aangeroepen. De standaardwaarde is 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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
* Library [Aspose.Slides](../../../)