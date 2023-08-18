---
title: ToArray()
second_title: Aspose.Slides for C++ API Reference
description: Creates and returns an array with all FallBack fonts for this rule.
type: docs
weight: 105
url: /aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() method


Creates and returns an array with all FallBack fonts for this rule.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Return Value

Array of [System::String](../../../system/string/)
## Remarks



```cpp
// Create a rule contains a list of fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Get all font-names as array
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) method


Creates and returns an array with all FallBack fonts from the specified range in list.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | An index of a first font to add. |
| count | **int32_t** | A number of fonts to add. |

### Return Value

Array of [System::String](../../../system/string/)
## Remarks



```cpp
// Create a rule contains a list of fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Get a last two font-names as array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)