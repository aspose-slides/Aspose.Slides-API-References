---
title: set_EmbedImages()
second_title: Aspose.Slides per C++ Riferimento API
description: Imposta l'opzione di incorporamento delle immagini. Scrivi bool.
type: docs
weight: 66
url: /it/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) metodo

Imposta l'opzione di incorporamento delle immagini. Scrivi **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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