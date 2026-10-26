---
title: get_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur false.
type: docs
weight: 183
url: /fr/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() method

Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu’elle est définie sur **true**, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures lors du rendu du texte

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Voir aussi

* Classe [IHtmlOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)