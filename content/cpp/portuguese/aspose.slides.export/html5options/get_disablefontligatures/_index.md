---
title: get_DisableFontLigatures()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como false.
type: docs
weight: 131
url: /pt/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() method


Obtém um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como **true**, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Desativar ligaduras na renderização de texto

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Veja também

* Classe [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)