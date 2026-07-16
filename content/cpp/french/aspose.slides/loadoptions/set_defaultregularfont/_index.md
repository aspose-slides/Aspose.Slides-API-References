---
title: set_DefaultRegularFont()
second_title: Référence API Aspose.Slides pour C++
description: "Définit la police Regular utilisée si la police source n'est pas trouvée. Écrivez System::String."
type: docs
weight: 40
url: /fr/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) méthode

Définit la police Regular utilisée si la police source n'est pas trouvée. Écrivez [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Remarques

L'exemple suivant montre comment définir les polices par défaut pour le rendu de PowerPoint [Presentation](../../presentation/).
```cpp
// Utilisez les options de chargement pour définir les polices régulières et asiatiques par défaut
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Chargez la présentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Générez la vignette de la diapositive
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Générez le PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Générez le XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)