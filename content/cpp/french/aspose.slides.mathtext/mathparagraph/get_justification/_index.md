---
title: get_Justification()
second_title: Référence API Aspose.Slides pour C++
description: "Paragraph Justification Valeur par défaut : CenteredAsGroup"
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() méthode

[Paragraph](../../../aspose.slides/paragraph/) Justification Valeur par défaut : CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Remarques

Exemple :
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Voir aussi

* Enum [MathJustification](../../mathjustification/)
* Classe [MathParagraph](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)