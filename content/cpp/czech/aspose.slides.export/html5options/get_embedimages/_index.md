---
title: get_EmbedImages()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací možnost vkládání obrázků. Čte bool.
type: docs
weight: 53
url: /cs/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metoda


Vrací volbu vkládání obrázků. Čte **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Viz také

* Třída [Html5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)