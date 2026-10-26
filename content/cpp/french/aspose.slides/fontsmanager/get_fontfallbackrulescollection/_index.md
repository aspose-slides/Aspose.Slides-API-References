---
title: get_FontFallBackRulesCollection()
second_title: Référence API Aspose.Slides pour C++
description: Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées grâce à la fonctionnalité de rappel. Lire IFontFallBackRulesCollection.
type: docs
weight: 27
url: /fr/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() méthode

Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substituts appropriés grâce à la fonctionnalité de rappel. Lire [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Remarques

```cpp
auto pres = MakeObject<Presentation>();
// Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// ajout de règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ou
// initialisation d'une nouvelle instance de collection de règles
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// ajout de règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// et remplacement de la collection existante par la nouvelle dans FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [FontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)