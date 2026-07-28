---
title: set_EmbedImages()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja a képek beágyazási opcióját. Írja bool.
type: docs
weight: 66
url: /hu/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metódus

Beállítja a képek beágyazási opcióját. Írja **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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