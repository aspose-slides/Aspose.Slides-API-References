---
title: get_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false.
type: docs
weight: 105
url: /fr/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() méthode

Renvoie une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est **true**, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures dans le rendu du texte

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Voir aussi

* Classe [Html5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)