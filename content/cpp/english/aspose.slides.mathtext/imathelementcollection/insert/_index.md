---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a math element into the collection at the specified index.
type: docs
weight: 53
url: /aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) method


Inserts a math element into the collection at the specified index.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which [IMathElement](../../imathelement/) should be inserted. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The [IMathElement](../../imathelement/) to insert. |
## Remarks



Example: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)