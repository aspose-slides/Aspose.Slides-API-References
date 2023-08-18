---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Gets the item at the specified index. Read-only IMathBlock.
type: docs
weight: 40
url: /aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) method


Gets the item at the specified index. Read-only [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item to get |

### Return Value

The block of a mathematical text.
## Remarks



Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)