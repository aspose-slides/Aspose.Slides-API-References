---
title: get_OutputPath()
second_title: Aspose.Slides para Referência da API C++
description: "Determina onde os recursos externos devem ser armazenados. Leia System::String."
type: docs
weight: 79
url: /pt/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() método


Determina onde os recursos externos devem ser armazenados. Leia [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Observações


Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IHtml5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)