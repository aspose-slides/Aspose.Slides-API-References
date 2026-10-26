---
title: get_OutputPath()
second_title: Referência da API Aspose.Slides para C++
description: "Determina onde os recursos externos devem ser armazenados. Leia System::String."
type: docs
weight: 79
url: /pt/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() método


Determina onde os recursos externos devem ser armazenados. Leia [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)