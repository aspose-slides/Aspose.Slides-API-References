---
title: set_DefaultRegularFont()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het reguliere lettertype in voor het geval het bronlettertype niet wordt gevonden. Schrijf System::String."
type: docs
weight: 40
url: /nl/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) methode

Stelt het reguliere lettertype in voor het geval het bronlettertype niet wordt gevonden. Schrijf [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Opmerkingen

Het volgende voorbeeld toont hoe u standaardlettertypen kunt instellen voor het renderen van PowerPoint [Presentation](../../presentation/). 
```cpp
// Gebruik load options om de standaard reguliere en Aziatische lettertypen te definiëren
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Laad de presentatie
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Genereer dia-miniatuur
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