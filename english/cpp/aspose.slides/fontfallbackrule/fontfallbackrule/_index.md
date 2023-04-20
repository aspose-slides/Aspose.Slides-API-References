---
title: FontFallBackRule()
second_title: Aspose.Slides for C++ API Reference
description: Creates new instance.
type: docs
weight: 66
url: /cpp/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructor


Creates new instance.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Start index of unicode range |
| endIndex | **uint32_t** | End index of unicode range |
| fontNames | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
// Create new instance of FantFallBackRule with one font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Create new instance of FantFallBackRule with several fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructor


Creates new instance.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Start index of unicode range |
| endIndex | **uint32_t** | End index of unicode range |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
// Create new instance of FantFallBackRule with two fonts
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Create new instance of FantFallBackRule with several fonts.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)