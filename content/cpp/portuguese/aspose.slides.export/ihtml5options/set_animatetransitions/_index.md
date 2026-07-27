---
title: set_AnimateTransitions()
second_title: Referência da API Aspose.Slides para C++
description: Define a opção de animação de transições. Escreva bool.
type: docs
weight: 14
url: /pt/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) method


Define a opção de animação de transições. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Veja Também

* Classe [IHtml5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)