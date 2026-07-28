---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API referencia
description: Beállítja azt a módot, amelyben a diák a lapon helyezkednek el a prezentáció exportálásakor ISlidesLayoutOptions.
type: docs
weight: 170
url: /hu/aspose.slides.export/html5options/set_slideslayoutoptions/
---
## Html5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metódus


Beállítja azt a módot, amelyben a diák a lapon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::Html5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Megjegyzés


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

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Osztály [Html5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)