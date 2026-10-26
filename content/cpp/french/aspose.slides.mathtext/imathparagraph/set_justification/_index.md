---
title: set_Justification()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Paragraph Justification Valeur par défaut : CenteredAsGroup"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) méthode

[Paragraph](../../../aspose.slides/paragraph/) Justification Valeur par défaut : CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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