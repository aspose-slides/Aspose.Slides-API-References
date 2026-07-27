---
title: get_DefaultRegularFont()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna a fonte Regular usada caso a fonte de origem não seja encontrada. Leia System::String."
type: docs
weight: 27
url: /pt/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() método

Retorna a fonte Regular usada caso a fonte de origem não seja encontrada. Leia [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Observações

O exemplo a seguir mostra como definir fontes padrão para renderizar PowerPoint [Presentation](../../presentation/).
```cpp
// Use opções de carregamento para definir as fontes regulares e asiáticas padrão
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

## Ver também

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)