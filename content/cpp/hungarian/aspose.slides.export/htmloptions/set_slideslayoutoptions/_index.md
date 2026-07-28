---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja azt a módot, amelyben a diák a lapra kerülnek a bemutató exportálása során az ISlidesLayoutOptions használatával.
type: docs
weight: 14
url: /hu/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metódus


Beállítja azt a módot, amelyben a diák a lapra kerülnek a bemutató exportálása közben [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Osztály [HtmlOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)