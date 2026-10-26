---
title: get_HandleRepeatedSpaces()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie comment les caractères d'espace réguliers répétés doivent être gérés lors de l'exportation Markdown.
type: docs
weight: 235
url: /fr/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const méthode


Spécifie comment les caractères d'espace réguliers répétés doivent être traités lors de l'exportation Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Remarques


Cette propriété définit si les espaces consécutifs sont :* conservés en tant que caractères d'espace réguliers,
* alternés entre espaces réguliers et entités d'espace insécable (**&nbsp;**),
* ou entièrement remplacés (après le premier) par **&nbsp;** pour préserver l'alignement visuel dans la sortie Markdown.



La valeur par défaut est [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Voir aussi

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Classe [MarkdownSaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)