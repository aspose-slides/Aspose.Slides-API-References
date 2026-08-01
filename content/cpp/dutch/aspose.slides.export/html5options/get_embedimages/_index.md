---
title: get_EmbedImages()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert de optie voor het insluiten van afbeeldingen. Lezen bool.
type: docs
weight: 53
url: /nl/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() methode

Retourneert de optie voor het insluiten van afbeeldingen. Lezen **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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