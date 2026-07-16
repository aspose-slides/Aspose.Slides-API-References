---
title: get_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 40
url: /fr/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() méthode

Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Remarques

Exemple:
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

* Classe [IRenderingOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)