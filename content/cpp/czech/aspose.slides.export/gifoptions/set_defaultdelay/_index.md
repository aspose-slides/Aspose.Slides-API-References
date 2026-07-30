---
title: set_DefaultDelay()
second_title: Reference API Aspose.Slides pro C++
description: "Nastaví výchozí čas prodlevy [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda ISlideShowTransition::set_AdvanceAfterTime(). Výchozí hodnota je 1000."
type: docs
weight: 92
url: /cs/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metoda


Nastaví výchozí čas prodlevy [ms]. Tato hodnota bude použita, pokud nebyla zavolána metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/). Výchozí hodnota je 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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