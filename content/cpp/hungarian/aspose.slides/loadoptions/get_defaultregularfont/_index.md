---
title: get_DefaultRegularFont()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja a szabályos betűtípust, ha a forrás betűtípusa nem található. Olvassa el System::String."
type: docs
weight: 27
url: /hu/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metódus

Visszaadja a szabványos betűtípust, ha a forrás betűtípusa nem található. Olvassa el [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Megjegyzések

A következő példa azt mutatja, hogyan lehet alapértelmezett betűtípusokat beállítani a PowerPoint [Presentation](../../presentation/) megjelenítéséhez.
```cpp
// Használja a betöltési beállításokat az alapértelmezett szabályos és ázsiai betűtípusok meghatározásához
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Töltse be a bemutatót
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Diakép bélyegkép generálása
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
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)