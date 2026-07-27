---
title: set_AnimateShapes()
second_title: Referência da API Aspose.Slides para C++
description: Define a opção de animação de formas. Escreva bool.
type: docs
weight: 40
url: /pt/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) método


Define a opção de animação de formas. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
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