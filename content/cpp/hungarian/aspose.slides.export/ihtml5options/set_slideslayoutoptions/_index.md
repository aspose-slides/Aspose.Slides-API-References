---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Referencia
description: Beállítja azt a módot, ahogyan a diák az oldalon helyezkednek el a prezentáció exportálása során ISlidesLayoutOptions.
type: docs
weight: 170
url: /hu/aspose.slides.export/ihtml5options/set_slideslayoutoptions/
---
## IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metódus

Beállítja azt a módot, ahogyan a diák az oldalon helyezkednek el a prezentáció exportálása során [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Osztály [IHtml5Options](../)
* Névterület [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)