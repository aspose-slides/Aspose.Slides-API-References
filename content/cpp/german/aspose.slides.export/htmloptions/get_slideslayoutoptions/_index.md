---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird ISlidesLayoutOptions.
type: docs
weight: 1
url: /de/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() Methode


Ermittelt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [HtmlOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)