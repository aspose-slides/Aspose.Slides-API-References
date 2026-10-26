---
title: set_EmbedImages()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in alternativ för inbäddning av bilder. Skriv bool.
type: docs
weight: 66
url: /sv/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metod


Ställer in alternativ för inbäddning av bilder. Skriver **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Se även

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)