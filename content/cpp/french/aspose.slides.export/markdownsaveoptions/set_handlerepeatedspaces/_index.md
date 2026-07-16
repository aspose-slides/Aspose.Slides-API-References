---
title: set_HandleRepeatedSpaces()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation en Markdown.
type: docs
weight: 248
url: /fr/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) méthode

Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Remarques

Cette propriété définit si les espaces consécutifs sont :
* conservés en tant que caractères d'espace réguliers,
* alternés entre des espaces réguliers et des entités d'espace insécable (**&nbsp;**),
* ou entièrement remplacés (après le premier) par **&nbsp;** pour préserver l'alignement visuel dans la sortie Markdown.

La valeur par défaut est [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Voir aussi

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Classe [MarkdownSaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)