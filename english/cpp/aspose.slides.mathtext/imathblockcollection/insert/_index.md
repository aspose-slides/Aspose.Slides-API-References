---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts IMathBlock into the collection at the specified index.
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) method


Inserts [IMathBlock](../../imathblock/) into the collection at the specified index.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which an item should be inserted. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | The [IMathBlock](../../imathblock/) to insert. |
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)