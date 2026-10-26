---
title: get_EmbedImages()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a opção de incorporação de imagens. Leitura bool.
type: docs
weight: 53
url: /pt/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() método


Retorna a opção de incorporação de imagens. Leitura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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