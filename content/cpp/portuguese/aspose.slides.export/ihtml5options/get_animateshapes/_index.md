---
title: get_AnimateShapes()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a opção de animação de formas. Leia bool.
type: docs
weight: 27
url: /pt/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() método


Retorna a opção de animação de formas. Leia **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Veja Também

* Classe [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)