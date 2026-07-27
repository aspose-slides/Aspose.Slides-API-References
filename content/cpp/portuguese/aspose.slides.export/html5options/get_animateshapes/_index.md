---
title: get_AnimateShapes()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a opção de animação de formas. Leitura bool.
type: docs
weight: 27
url: /pt/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() método

Retorna a opção de animação de formas. Leitura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Classe [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)