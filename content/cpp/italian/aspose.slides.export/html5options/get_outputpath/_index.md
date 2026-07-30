---
title: get_OutputPath()
second_title: Riferimento API Aspose.Slides per C++
description: "Determina dove devono essere memorizzate le risorse esterne. Leggi System::String."
type: docs
weight: 79
url: /it/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metodo


Determina dove devono essere memorizzate le risorse esterne. Leggi [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Html5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)