---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new font(s) to the list of FallBack fonts.
type: docs
weight: 40
url: /cpp/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) method


Adds a new font(s) to the list of FallBack fonts.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
//Create of new instance of FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Add a second font to the rule
newRule->AddFallBackFonts(u"MS Gothic");
//Add a third and fourth fonts to the rule
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) method


Adds a new fonts to the list of FallBack fonts.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## Remarks



```cpp
//Create of new instance of FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Add of another three fonts to the rule
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)