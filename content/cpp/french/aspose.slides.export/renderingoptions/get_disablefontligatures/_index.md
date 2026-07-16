---
title: get_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 40
url: /fr/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() méthode


Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est définie sur **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Remarques


Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures dans le rendu du texte

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Voir aussi

* Classe [RenderingOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)