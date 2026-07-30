---
title: get_DefaultRegularFont()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací běžné písmo použité v případě, že zdrojové písmo není nalezeno. Přečtěte si System::String."
type: docs
weight: 27
url: /cs/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metoda

Vrací běžné písmo použité v případě, že zdrojové písmo není nalezeno. Přečtěte si [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Poznámky

Následující příklad ukazuje, jak nastavit výchozí písma pro vykreslování PowerPoint [Presentation](../../presentation/). 
```cpp
// Použijte možnosti načítání k nastavení výchozích běžných a asijských písem
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Načtěte prezentaci
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Vytvořte miniaturu snímku
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Vytvořte PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Vytvořte XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)