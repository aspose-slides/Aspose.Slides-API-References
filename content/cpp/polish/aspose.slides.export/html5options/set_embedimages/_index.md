---
title: set_EmbedImages()
second_title: Referencja API Aspose.Slides dla C++
description: Ustawia opcję osadzania obrazów. Zapisz bool.
type: docs
weight: 66
url: /pl/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metoda

Ustawia opcję osadzania obrazów. Zapisz **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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