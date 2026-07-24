---
title: set_EmbedImages()
second_title: Aspose.Slides für C++ API Referenz
description: Legt die Option zum Einbetten von Bildern fest. Schreiben bool.
type: docs
weight: 66
url: /de/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) Methode


Legt die Option zum Einbetten von Bildern fest. Schreiben **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## Hinweise


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