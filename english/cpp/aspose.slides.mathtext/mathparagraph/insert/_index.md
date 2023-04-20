---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts IMathBlock into the collection at the specified index.
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) method


Inserts [IMathBlock](../../imathblock/) into the collection at the specified index.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which an item should be inserted. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The [IMathBlock](../../imathblock/) to insert. |
## Remarks



Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)