---
title: get_OutputPath()
second_title: Aspose.Slides per C++ Riferimento API
description: "Determina dove devono essere archiviate le risorse esterne. Leggi System::String."
type: docs
weight: 79
url: /it/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metodo


Determina dove devono essere archiviate le risorse esterne. Leggi [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Note


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