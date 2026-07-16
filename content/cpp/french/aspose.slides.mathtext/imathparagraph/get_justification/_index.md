---
title: get_Justification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Justification du paragraphe Valeur par défaut : CenteredAsGroup"
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() méthode


[Paragraph](../../../aspose.slides/paragraph/) Justification Valeur par défaut : CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Remarques


Exemple : 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Voir aussi

* Énum [MathJustification](../../mathjustification/)
* Classe [IMathParagraph](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)