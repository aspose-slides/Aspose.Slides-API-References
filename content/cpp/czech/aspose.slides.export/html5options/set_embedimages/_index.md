---
title: set_EmbedImages()
second_title: Aspose.Slides pro C++ API referenci
description: Nastavuje možnost vkládání obrázků. Zapište bool.
type: docs
weight: 66
url: /cs/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metoda


Nastavuje možnost vkládání obrázků. Zapište **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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