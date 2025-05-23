---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Returns an index of the specified rule in the collection.
type: docs
weight: 118
url: /aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) method


Returns an index of the specified rule in the collection.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name to find. |

### Return Value

Index of a font or -1 if font not found in list.
## Remarks



```cpp
// Create a rule contains a list of fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Get index of Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## See Also

* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)