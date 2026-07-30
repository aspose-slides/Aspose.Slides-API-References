---
title: get_EmbedImages()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'opzione di incorporamento delle immagini. Solo lettura bool.
type: docs
weight: 53
url: /it/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() metodo


Restituisce l'opzione di incorporamento delle immagini. Solo lettura **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## Note


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Vedi anche

* Classe [IHtml5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)