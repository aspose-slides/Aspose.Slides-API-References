---
title: set_EmbedImages()
second_title: Referência da API Aspose.Slides para C++
description: Define a opção de incorporação de imagens. Escreva bool.
type: docs
weight: 66
url: /pt/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) método


Define a opção de incorporação de imagens. Escreva **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Veja Também

* Classe [Html5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)