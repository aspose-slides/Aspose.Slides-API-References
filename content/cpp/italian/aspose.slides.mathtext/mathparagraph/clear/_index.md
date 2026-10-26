---
title: Clear()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove tutti gli elementi dalla collezione.
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metodo

Rimuove tutti gli elementi dalla collezione.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Osservazioni

Esempio: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Vedi anche

* Classe [MathParagraph](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)