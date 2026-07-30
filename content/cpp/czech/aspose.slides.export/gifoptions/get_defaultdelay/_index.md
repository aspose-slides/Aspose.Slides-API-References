---
title: get_DefaultDelay()
second_title: Aspose.Slides pro C++ referenční příručku API
description: "Získá výchozí čas zpoždění [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda ISlideShowTransition::set_AdvanceAfterTime(). Výchozí hodnota je 1000."
type: docs
weight: 79
url: /cs/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() method


Získá výchozí čas zpoždění [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). Výchozí hodnota je 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Viz také

* Třída [GifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)