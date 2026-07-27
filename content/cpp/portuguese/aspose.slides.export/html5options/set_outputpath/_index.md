---
title: set_OutputPath()
second_title: Referência da API Aspose.Slides para C++
description: "Determina onde os recursos externos devem ser armazenados. Escreva System::String."
type: docs
weight: 92
url: /pt/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) método


Determina onde os recursos externos devem ser armazenados. Escreva [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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

## Veja também

* Classe [String](../../../system/string/)
* Classe [Html5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)