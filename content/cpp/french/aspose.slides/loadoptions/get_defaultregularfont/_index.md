---
title: get_DefaultRegularFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie la police Regular utilisée si la police source n'est pas trouvée. Lire System::String."
type: docs
weight: 27
url: /fr/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() méthode

Renvoie la police Regular utilisée si la police source n'est pas trouvée. Lire [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Remarques

L'exemple suivant montre comment définir les polices par défaut pour le rendu PowerPoint [Presentation](../../presentation/). 
```cpp
// Utilisez les options de chargement pour définir les polices régulières et asiatiques par défaut
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Charger la présentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Générer le PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Générer le XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)