---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new font(s) to the list of FallBack fonts.
type: docs
weight: 79
url: /aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) method


Adds a new font(s) to the list of FallBack fonts.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
// Create new instance of FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Add a second font to the rule
newRule->AddFallBackFonts(u"MS Gothic");
//Add a third and fourth fonts to the rule
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) method


Adds a new fonts to the list of FallBack fonts.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
//Create new instance of FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Add of another three fonts to the rule
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)