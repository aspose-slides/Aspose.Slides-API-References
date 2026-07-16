---
title: Clear()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime tous les éléments de la collection.
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() méthode


Supprime tous les éléments de la collection.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Remarques


Exemple: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Voir aussi

* Classe [MathParagraph](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)