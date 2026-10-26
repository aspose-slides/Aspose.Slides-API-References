---
title: set_EmbedImages()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de optie voor het insluiten van afbeeldingen in. Schrijf bool.
type: docs
weight: 66
url: /nl/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) methode

Stelt de optie voor het insluiten van afbeeldingen in. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zie ook

* Klasse [IHtml5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)