---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la règle à l'index spécifié. Lecture seule IFontFallBackRule.
type: docs
weight: 1
url: /fr/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) méthode

Obtient la règle à l'index spécifié. Lecture seule [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Remarques



```cpp
auto pres = MakeObject<Presentation>();
//Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Ajout de plusieurs règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Récupération de l'objet de la première règle dans la collection
auto firstRule = rulesList->idx_get(0);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [IFontFallBackRulesCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)