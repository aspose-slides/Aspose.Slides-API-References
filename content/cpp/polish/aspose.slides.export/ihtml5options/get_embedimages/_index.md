---
title: get_EmbedImages()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca opcję osadzania obrazów. Odczyt bool.
type: docs
weight: 53
url: /pl/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() method


Zwraca opcję osadzania obrazów. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
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