---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API Reference
description: Replace font in presentation
type: docs
weight: 118
url: /aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) method


Replace font in presentation

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Source font |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Destination font |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) method


Replace font in presentation using information provided in [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Font substitution info |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) method


Replace font in presentation using information provided in collection of [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Font substitution rules collection |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)