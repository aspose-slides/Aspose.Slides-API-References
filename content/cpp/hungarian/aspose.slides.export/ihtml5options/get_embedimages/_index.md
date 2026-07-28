---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaadja a képek beágyazási opcióját. Olvasás **bool**.
type: docs
weight: 53
url: /hu/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() metódus


Visszaadja a képek beágyazási beállítását. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
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

* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)