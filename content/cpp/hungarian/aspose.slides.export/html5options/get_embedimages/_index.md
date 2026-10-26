---
title: get_EmbedImages()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a képek beágyazásának beállítását. Olvasandó bool.
type: docs
weight: 53
url: /hu/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metódus


Visszaadja a képek beágyazásának beállítását. Olvasás **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Lásd még

* Osztály [Html5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)