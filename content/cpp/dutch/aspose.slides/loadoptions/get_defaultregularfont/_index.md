---
title: get_DefaultRegularFont()
second_title: Aspose.Slides voor C++ API Referentie
description: "Retourneert het Regular-lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lees System::String."
type: docs
weight: 27
url: /nl/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() methode


Retourneert het Regular-lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lees [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe u standaardlettertypen kunt instellen voor het renderen van PowerPoint [Presentation](../../presentation/). 
```cpp
// Gebruik loadopties om de standaard regular- en asian-lettertypen te definiëren
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Laad de presentatie
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Genereer dia-thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Genereer PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Genereer XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)