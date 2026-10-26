---
title: ReplaceFont()
second_title: Aspose.Slides für C++ API Referenz
description: Schriftart in der Präsentation ersetzen
type: docs
weight: 118
url: /de/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) Methode

Schriftart in der Präsentation ersetzen

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Quellschriftart |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Zielschriftart |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) Methode

Schriftart in der Präsentation ersetzen unter Verwendung der in [IFontSubstRule](../../ifontsubstrule/) bereitgestellten Informationen

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Information zur Schriftart-Substitution |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) Methode

Schriftart in der Präsentation ersetzen unter Verwendung der in der Sammlung von [IFontSubstRule](../../ifontsubstrule/) bereitgestellten Informationen

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Sammlung von Informationen zur Schriftart-Substitution |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontData](../../ifontdata/)
* Klasse [IFontsManager](../)
* Klasse [IFontSubstRule](../../ifontsubstrule/)
* Klasse [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)