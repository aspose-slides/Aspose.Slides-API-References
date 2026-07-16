---
title: ToLatex()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient l'équation mathématique au format LaTeX
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() méthode

Obtient l'équation mathématique au format LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Remarques

Exemple : 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [MathParagraph](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)