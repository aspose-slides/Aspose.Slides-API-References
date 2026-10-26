---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoutez une nouvelle règle FallBack à la fin de la collection.
type: docs
weight: 14
url: /fr/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) méthode

Ajoutez une nouvelle règle FallBack à la fin de la collection.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Règle spécifiée pour l'ajout |
## Remarques



```cpp
auto pres = MakeObject<Presentation>();
//Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Ajout d'une nouvelle règle à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [IFontFallBackRulesCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)