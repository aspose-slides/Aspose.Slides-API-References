---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden, ISlidesLayoutOptions.
type: docs
weight: 157
url: /de/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() Methode


Ermittelt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)