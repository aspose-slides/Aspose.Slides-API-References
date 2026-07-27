---
title: get_DisableFontLigatures()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como false.
type: docs
weight: 326
url: /pt/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() method

Obtém um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como **true**, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como **false**.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Desativar ligaduras na renderização de texto

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Veja Também

* Classe [SVGOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)