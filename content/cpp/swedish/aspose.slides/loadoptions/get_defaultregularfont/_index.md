---
title: get_DefaultRegularFont()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar vanligt teckensnitt som används om källeteckensnittet inte hittas. Läs System::String."
type: docs
weight: 27
url: /sv/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metod


Returnerar vanligt teckensnitt som används om källeteckensnittet inte hittas. Läs [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Anmärkningar


Följande exempel visar hur man ställer in standardteckensnitt för rendering av PowerPoint [Presentation](../../presentation/).
```cpp
// Använd laddningsalternativ för att definiera de standardvanliga och asiatiska teckensnitten
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Läs in presentationen
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Skapa bild för bildspelsminiatur
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Skapa PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Skapa XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)