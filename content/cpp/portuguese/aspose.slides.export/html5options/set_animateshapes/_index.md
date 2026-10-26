---
title: set_AnimateShapes()
second_title: Aspose.Slides para Referência da API C++
description: Define a opção de animação de formas. Escreva bool.
type: docs
weight: 40
url: /pt/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) método


Define a opção de animação de formas. Escreva **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Veja também

* Classe [Html5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)