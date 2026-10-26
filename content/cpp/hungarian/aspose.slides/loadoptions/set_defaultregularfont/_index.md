---
title: set_DefaultRegularFont()
second_title: Aspose.Slides C++ API Referencia
description: "Beállítja a reguláris betűtípust, ha a forrás betűtípusa nem található. Írja be System::String."
type: docs
weight: 40
url: /hu/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metódus

Beállítja a reguláris betűtípust, ha a forrás betűtípusa nem található. Írja be [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Megjegyzések

Az alábbi példa bemutatja, hogyan állítható be az alapértelmezett betűtípus a PowerPoint [Presentation](../../presentation/) megjelenítéséhez. 
```cpp
// Használja a betöltési beállításokat az alapértelmezett reguláris és ázsiai betűtípusok meghatározásához
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Töltse be a bemutatót
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Diakép előállítása
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF generálása
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS generálása
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [LoadOptions](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)