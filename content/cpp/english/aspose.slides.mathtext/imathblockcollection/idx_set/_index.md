---
title: idx_set()
second_title: Aspose.Slides for C++ API Reference
description: Gets the item at the specified index. Read-only IMathBlock.
type: docs
weight: 105
url: /aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) method


Gets the item at the specified index. Read-only [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item to get |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The block of a mathematical text. |
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)