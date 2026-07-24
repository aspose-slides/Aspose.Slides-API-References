---
title: set_DefaultRegularFont()
second_title: Aspose.Slides für C++ API Referenz
description: "Legt die Standardschriftart fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreiben Sie System::String."
type: docs
weight: 40
url: /de/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) Methode

Legt die Standardschriftart fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreiben Sie [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Hinweise

Das folgende Beispiel zeigt, wie man Standard-Schriftarten für das Rendering von PowerPoint [Presentation](../../presentation/) festlegt.
```cpp
// Verwenden Sie Ladeoptionen, um die Standard-Regular- und Asian-Schriftarten festzulegen
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Load the presentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generate PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generate XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)