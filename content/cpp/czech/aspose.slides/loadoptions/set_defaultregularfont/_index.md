---
title: set_DefaultRegularFont()
second_title: Aspose.Slides pro referenci API C++
description: "Nastavuje standardní písmo používané v případě, že zdrojové písmo není nalezeno. Zapište System::String."
type: docs
weight: 40
url: /cs/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metoda

Nastavuje standardní písmo používané v případě, že zdrojové písmo není nalezeno. Zapište [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Poznámky

Následující příklad ukazuje, jak nastavit výchozí písma pro vykreslování PowerPoint [Presentation](../../presentation/).
```cpp
// Použijte možnosti načítání k definování výchozích běžných a asijských písem
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

* třída [String](../../../system/string/)
* třída [LoadOptions](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)