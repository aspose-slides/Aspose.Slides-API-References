---
title: ReplaceFont()
second_title: Aspose.Slides per C++ Riferimento API
description: Sostituisci il font nella presentazione
type: docs
weight: 118
url: /it/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) metodo


Sostituisci il font nella presentazione

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font di origine |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font di destinazione |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) metodo


Sostituisci il font nella presentazione usando le informazioni fornite in [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Informazioni di sostituzione del font |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) metodo


Sostituisci il font nella presentazione usando le informazioni fornite nella collezione di [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Collezione di informazioni di sostituzione del font |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [IFontsManager](../)
* Classe [IFontSubstRule](../../ifontsubstrule/)
* Classe [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)