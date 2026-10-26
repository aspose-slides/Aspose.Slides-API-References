---
title: get_ParagraphFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'objet de formatage pour ce paragraphe. Lecture seule IParagraphFormat.
type: docs
weight: 14
url: /fr/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() méthode

Renvoie l'objet de formatage pour ce paragraphe. Lecture seule [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Remarques

L'objet de formatage contient les paramètres de formatage définis uniquement pour le paragraphe actuel, les données héritées ne sont pas appliquées.

Pour obtenir les valeurs effectives, y compris celles héritées, utilisez la méthode [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormat](../../iparagraphformat/)
* Classe [Paragraph](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)