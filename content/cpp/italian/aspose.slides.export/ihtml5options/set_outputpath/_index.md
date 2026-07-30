---
title: set_OutputPath()
second_title: Riferimento API di Aspose.Slides per C++
description: "Determina dove devono essere archiviati le risorse esterne. Scrivi System::String."
type: docs
weight: 92
url: /it/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) metodo


Determina dove dovrebbero essere archiviati le risorse esterne. Scrivi [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## Osservazioni


Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IHtml5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)