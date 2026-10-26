---
title: set_DefaultRegularFont()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in standardfont som används om källfonten inte hittas. Skriv System::String."
type: docs
weight: 40
url: /sv/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metod

Ställer in standardfont som används om källfonten inte hittas. Skriv [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Anmärkningar

Följande exempel visar hur man ställer in standardfonter för rendering av PowerPoint [Presentation](../../presentation/). 
```cpp
// Använd laddningsalternativ för att definiera standardregular- och asiatisk-typsnitt
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Läs in presentationen
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generera miniatyrbild för bilden
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generera PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generera XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)