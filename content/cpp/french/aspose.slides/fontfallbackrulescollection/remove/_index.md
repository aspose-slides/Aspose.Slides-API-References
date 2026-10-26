---
title: Remove()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la première occurrence d'une règle FallBack spécifique de la collection.
type: docs
weight: 53
url: /fr/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) méthode

Supprime la première occurrence d'une règle FallBack spécifique de la collection.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | La règle à supprimer de la collection. |

## Remarques



```cpp
auto pres = MakeObject<Presentation>();
//Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Ajout de plusieurs règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Récupération de l'objet de la première règle de la collection
auto firstRule = rulesList->idx_get(0);
//Suppression
rulesList->Remove(firstRule);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)