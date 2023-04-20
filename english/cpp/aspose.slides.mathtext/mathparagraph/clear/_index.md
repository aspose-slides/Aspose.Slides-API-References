---
title: Clear()
second_title: Aspose.Slides for C++ API Reference
description: Removes all elements from the collection.
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() method


Removes all elements from the collection.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Remarks


Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## See Also

* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)