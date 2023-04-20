---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Reference
description: Removes the FallBack font at the specified index of the list.
type: docs
weight: 92
url: /cpp/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) method


Removes the FallBack font at the specified index of the list.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the font to remove. |
## Remarks



```cpp
// Create a rule contains a list of fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Removing of Tahoma from list
newRule->RemoveAt(2);
```


## See Also

* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)