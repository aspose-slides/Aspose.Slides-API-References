---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the collection contains a specific value.
type: docs
weight: 118
url: /aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) method


Determines whether the collection contains a specific value.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The object to locate in the collection. |

### Return Value

true if *mathBlock*  is found in the collection; otherwise, false.
## Remarks



Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)