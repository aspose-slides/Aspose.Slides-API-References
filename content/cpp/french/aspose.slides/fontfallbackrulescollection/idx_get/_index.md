---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la règle à l'index spécifié. Lecture seule IFontFallBackRule.
type: docs
weight: 66
url: /fr/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) méthode


Obtient la règle à l'index spécifié. Lecture seule [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Remarques



```cpp
auto pres = MakeObject<Presentation>();
//Obtention d'une collection de regles vide ou preinitialisee depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Ajout de plusieurs regles a la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recuperation de l'objet de la premiere regle de la collection
auto firstRule = rulesList->idx_get(0);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)