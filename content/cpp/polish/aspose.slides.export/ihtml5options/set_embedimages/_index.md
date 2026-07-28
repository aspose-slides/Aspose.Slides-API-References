---
title: set_EmbedImages()
second_title: Aspose.Slides – referencja API C++
description: Ustawia opcję osadzania obrazów. Zapisz bool.
type: docs
weight: 66
url: /pl/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) metoda


Ustawia opcję osadzania obrazów. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zobacz także

* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)