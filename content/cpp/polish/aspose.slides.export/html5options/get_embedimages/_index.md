---
title: get_EmbedImages()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zwraca opcję osadzania obrazów. Odczyt bool.
type: docs
weight: 53
url: /pl/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metoda


Zwraca opcję osadzania obrazów. Odczyt **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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

* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)