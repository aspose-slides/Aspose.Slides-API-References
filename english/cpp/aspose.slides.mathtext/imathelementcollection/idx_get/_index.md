---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Gets the element at the specified index. Read-only IMathElement.
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(**int32_t**) method


Gets the element at the specified index. Read-only [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item to get |
## Remarks



Example: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
