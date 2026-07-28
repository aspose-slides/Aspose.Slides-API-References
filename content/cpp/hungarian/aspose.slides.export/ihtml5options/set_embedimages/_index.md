---
title: set_EmbedImages()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja a képek beágyazási lehetőségét. Írja bool.
type: docs
weight: 66
url: /hu/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) method


Beállítja a képek beágyazási lehetőségét. Írja **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
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
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)