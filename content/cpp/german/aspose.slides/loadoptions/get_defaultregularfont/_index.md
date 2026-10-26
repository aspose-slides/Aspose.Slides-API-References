---
title: get_DefaultRegularFont()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Standardschriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen Sie System::String."
type: docs
weight: 27
url: /de/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() Methode

Gibt die Standardschriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen Sie [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Hinweise

Das folgende Beispiel zeigt, wie Standard-Schriftarten für die Darstellung von PowerPoint [Presentation](../../presentation/) festgelegt werden.
```cpp
// Verwenden Sie Ladeoptionen, um die Standard-Regular- und Asian-Schriftarten zu definieren
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Präsentation laden
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Miniaturbild der Folie erzeugen
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF erzeugen
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS erzeugen
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Siehe auch

* Class [String](../../../system/string/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)