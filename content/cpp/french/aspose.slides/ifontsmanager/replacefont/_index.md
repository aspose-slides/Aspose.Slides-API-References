---
title: ReplaceFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplacer la police dans la présentation
type: docs
weight: 118
url: /fr/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method

Remplacer la police dans la présentation

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Police source |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Police de destination |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method

Remplacer la police dans la présentation en utilisant les informations fournies dans [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Informations de substitution de police |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method

Remplacer la police dans la présentation en utilisant les informations fournies dans la collection de [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Collection d'informations de substitution de police |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [IFontsManager](../)
* Classe [IFontSubstRule](../../ifontsubstrule/)
* Classe [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)