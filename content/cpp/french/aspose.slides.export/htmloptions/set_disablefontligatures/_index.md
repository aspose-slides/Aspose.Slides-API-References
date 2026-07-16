---
title: set_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides for C++
description: Définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 105
url: /fr/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) méthode


Définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsqu'il est défini sur **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures dans le rendu du texte

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Voir aussi

* Classe [HtmlOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)