---
title: get_MathParagraph()
second_title: Référence de l'API Aspose.Slides pour C++
description: Paragraphe mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() méthode


Paragraphe mathématique

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathParagraph](../../imathparagraph/)
* Classe [IMathPortion](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)