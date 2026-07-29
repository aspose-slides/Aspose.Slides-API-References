---
title: get_EmbedImages()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alternativ för bildinbäddning. Läs bool.
type: docs
weight: 53
url: /sv/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metod


Returnerar alternativet för bildinbäddning. Läs **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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