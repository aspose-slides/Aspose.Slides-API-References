---
title: set_DisableFontLigatures()
second_title: Référence API Aspose.Slides pour C++
description: Définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 196
url: /fr/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) méthode

Définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Remarques

Exemple:
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