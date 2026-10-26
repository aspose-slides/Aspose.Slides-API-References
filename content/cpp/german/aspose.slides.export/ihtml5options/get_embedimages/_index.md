---
title: get_EmbedImages()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Option zum Einbetten von Bildern zurück. Bool lesen.
type: docs
weight: 53
url: /de/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() Methode


Gibt die Option zum Einbetten von Bildern zurück. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Siehe auch

* Klasse [IHtml5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)