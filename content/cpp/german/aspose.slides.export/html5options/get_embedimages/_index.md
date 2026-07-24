---
title: get_EmbedImages()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Option zum Einbetten von Bildern zurück. Lese bool.
type: docs
weight: 53
url: /de/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() Methode


Gibt die Option zum Einbetten von Bildern zurück. Lese **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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

* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)