---
title: ReplaceFont()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nahradí písmo v prezentaci
type: docs
weight: 118
url: /cs/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method

Nahradit písmo v prezentaci

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Zdrojové písmo |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Cílové písmo |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method

Nahradit písmo v prezentaci pomocí informací poskytnutých v [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Informace o nahrazení písma |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method

Nahradit písmo v prezentaci pomocí informací poskytnutých v kolekci [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Kolekce informací o nahrazení písma |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontData](../../ifontdata/)
* Třída [IFontsManager](../)
* Třída [IFontSubstRule](../../ifontsubstrule/)
* Třída [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)