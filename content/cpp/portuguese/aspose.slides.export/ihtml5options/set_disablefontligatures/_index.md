---
title: set_DisableFontLigatures()
second_title: Aspose.Slides para C++ Referência da API
description: Define um valor indicando se o texto é renderizado sem usar ligações tipográficas. Quando definido como true, as ligações tipográficas serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como false.
type: docs
weight: 144
url: /pt/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) método

Define um valor que indica se o texto é renderizado sem usar ligações tipográficas. Quando definido como **true**, as ligações tipográficas serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Desativa ligações tipográficas na renderização de texto

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Ver também

* Classe [IHtml5Options](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)