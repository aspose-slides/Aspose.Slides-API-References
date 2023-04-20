---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds IMathBlock to the end of collection.
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) method


Adds [IMathBlock](../../imathblock/) to the end of collection.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A mathematical block that will be added to the end of the collection |
## Remarks



Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)