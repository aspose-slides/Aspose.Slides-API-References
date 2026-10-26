---
title: get_EmbedImages()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'opzione di incorporamento delle immagini. Lettura bool.
type: docs
weight: 53
url: /it/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() metodo


Restituisce l'opzione di incorporamento delle immagini. Lettura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Vedi anche

* Classe [Html5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)