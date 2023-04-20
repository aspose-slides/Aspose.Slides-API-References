---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the collection contains a specific value.
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) method


Determines whether the collection contains a specific value.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The object to locate in the collection. |

### Return Value

true if *item*  is found in the collection; otherwise, false.
## Remarks



Example: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)