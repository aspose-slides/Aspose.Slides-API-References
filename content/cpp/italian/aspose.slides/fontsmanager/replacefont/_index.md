---
title: ReplaceFont()
second_title: Riferimento API Aspose.Slides per C++
description: Sostituisci il font nella presentazione
type: docs
weight: 118
url: /it/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) metodo

Sostituisci il font nella presentazione

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Font di origine |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Font di destinazione |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) metodo

Sostituisci il font nella presentazione usando le informazioni fornite in [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Informazioni di sostituzione del font |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) metodo

Sostituisci il font nella presentazione usando le informazioni fornite nella collezione di [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Collezione di regole di sostituzione del font |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [FontsManager](../)
* Classe [IFontSubstRule](../../ifontsubstrule/)
* Classe [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)