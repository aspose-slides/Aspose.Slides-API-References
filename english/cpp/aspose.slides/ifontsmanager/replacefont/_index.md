---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API Reference
description: Replace font in presentation
type: docs
weight: 118
url: /cpp/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method


Replace font in presentation

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Source font |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Destination font |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method


Replace font in presentation using information provided in [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Font substitution info |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method


Replace font in presentation using information provided in collection of [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Font substitution info collection |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)