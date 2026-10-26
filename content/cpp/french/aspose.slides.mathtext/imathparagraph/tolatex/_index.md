---
title: ToLatex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'équation mathématique au format LaTeX
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() méthode

Obtient l'équation mathématique au format LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Remarques

Exemple:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IMathParagraph](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)