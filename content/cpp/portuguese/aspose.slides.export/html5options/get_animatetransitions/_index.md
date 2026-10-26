---
title: get_AnimateTransitions()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a opção de animação de transições. Leia bool.
type: docs
weight: 1
url: /pt/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() método


Retorna opção de animação de transições. Leia **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Veja também

* Classe [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)