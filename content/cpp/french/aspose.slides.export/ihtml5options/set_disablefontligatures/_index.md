---
title: set_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false.
type: docs
weight: 118
url: /fr/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) méthode


Définit une valeur indiquant si le texte est rendu sans utiliser les ligatures. Lorsqu'elle est définie sur **true**, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures lors du rendu du texte

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Voir aussi

* Classe [IHtml5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)