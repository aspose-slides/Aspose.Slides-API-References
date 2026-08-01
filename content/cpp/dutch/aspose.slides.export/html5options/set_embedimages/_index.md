---
title: set_EmbedImages()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de optie voor het insluiten van afbeeldingen in. Schrijf bool.
type: docs
weight: 66
url: /nl/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) methode


Stelt de optie voor het insluiten van afbeeldingen in. Schrijf **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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

* Klasse [Html5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)