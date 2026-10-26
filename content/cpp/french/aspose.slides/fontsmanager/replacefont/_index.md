---
title: ReplaceFont()
second_title: Référence API Aspose.Slides pour C++
description: Remplace la police dans la présentation
type: docs
weight: 118
url: /fr/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) méthode

Remplace la police dans la présentation

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Police source |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Police de destination |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) méthode

Remplace la police dans la présentation en utilisant les informations fournies dans [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Informations de substitution de police |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) méthode

Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Collection de règles de substitution de police |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [FontsManager](../)
* Classe [IFontSubstRule](../../ifontsubstrule/)
* Classe [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)