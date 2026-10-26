---
title: set_Justification()
second_title: Référence API Aspose.Slides for C++
description: "Justification du paragraphe Valeur par défaut: CenteredAsGroup"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) méthode


[Paragraph](../../../aspose.slides/paragraph/) Valeur par défaut de Justification : CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)