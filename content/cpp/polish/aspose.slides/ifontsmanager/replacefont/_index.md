---
title: ReplaceFont()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Zastąp czcionkę w prezentacji
type: docs
weight: 118
url: /pl/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) metoda


Zastąp czcionkę w prezentacji

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Czcionka źródłowa |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Czcionka docelowa |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) metoda


Zastąp czcionkę w prezentacji, używając informacji podanych w [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Informacje o podstawianiu czcionek |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) metoda


Zastąp czcionkę w prezentacji, używając informacji podanych w kolekcji [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Kolekcja informacji o podstawianiu czcionek |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)