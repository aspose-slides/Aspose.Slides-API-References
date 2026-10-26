---
title: ReplaceFont()
second_title: Aspose.Slides för C++ API-referens
description: Ersätt teckensnitt i presentationen
type: docs
weight: 118
url: /sv/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) metod

Byt ut teckensnitt i presentationen

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Källteckensnitt |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Måleteckensnitt |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) metod

Byt ut teckensnitt i presentationen med information som ges i [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Information om teckensnittsersättning |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) metod

Byt ut teckensnitt i presentationen med information som ges i samling av [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Samling av information om teckensnittsersättning |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontData](../../ifontdata/)
* Klass [IFontsManager](../)
* Klass [IFontSubstRule](../../ifontsubstrule/)
* Klass [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)