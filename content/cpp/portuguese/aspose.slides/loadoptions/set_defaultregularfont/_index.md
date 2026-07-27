---
title: set_DefaultRegularFont()
second_title: Aspose.Slides para C++ Referência da API
description: "Define a fonte Regular usada caso a fonte de origem não seja encontrada. Escreva System::String."
type: docs
weight: 40
url: /pt/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) método


Define a fonte Regular usada caso a fonte de origem não seja encontrada. Escreva [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Observações


O exemplo a seguir mostra como definir fontes padrão para a renderização do PowerPoint [Presentation](../../presentation/). 
```cpp
// Use opções de carregamento para definir as fontes padrão regular e asiática
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Carregar a apresentação
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Gerar miniatura do slide
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Gerar PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Gerar XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)