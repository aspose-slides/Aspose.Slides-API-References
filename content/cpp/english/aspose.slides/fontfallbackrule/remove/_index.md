---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of a specific FallBack font from the list.
type: docs
weight: 118
url: /aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) method


Removes the first occurrence of a specific FallBack font from the list.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | The font's name to remove from the list. |
## Remarks



```cpp
// Create a rule contains a list of fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Remove Tahoma from the list.
newRule->Remove(u"Tahoma");
```


## See Also

* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)