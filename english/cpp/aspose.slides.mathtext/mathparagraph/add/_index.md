---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds IMathBlock to the end of collection.
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add([System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\>) method


Adds [IMathBlock](../../imathblock/) to the end of collection.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A mathematical block that will be added to the end of the collection |
## Remarks



Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
