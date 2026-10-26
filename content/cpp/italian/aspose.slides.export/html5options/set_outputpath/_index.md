---
title: set_OutputPath()
second_title: Riferimento API Aspose.Slides per C++
description: "Determina dove devono essere archiviate le risorse esterne. Scrivi System::String."
type: docs
weight: 92
url: /it/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metodo


Determina dove devono essere archiviate le risorse esterne. Scrivi [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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