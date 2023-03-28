---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Reference
description: Removes an item at the specified index of the collection.
type: docs
weight: 157
url: /cpp/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(**int32_t**) method


Removes an item at the specified index of the collection.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item to remove. |
## Remarks



Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## See Also

* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
