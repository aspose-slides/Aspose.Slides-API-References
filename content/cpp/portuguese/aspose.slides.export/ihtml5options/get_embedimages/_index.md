---
title: get_EmbedImages()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna a opção de incorporação de imagens. Leitura **bool**.
type: docs
weight: 53
url: /pt/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() método

Retorna a opção de incorporação de imagens. Leitura **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
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

* Classe [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)