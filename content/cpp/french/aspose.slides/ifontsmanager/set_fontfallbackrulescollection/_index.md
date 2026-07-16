---
title: set_FontFallBackRulesCollection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la collection d'un utilisateur des règles FontFallBack pour la gestion des collections de polices afin d'effectuer les substitutions appropriées grâce à la fonctionnalité de repli. Écrire IFontFallBackRulesCollection.
type: docs
weight: 40
url: /fr/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) méthode

Représente la collection d’un utilisateur des règles FontFallBack pour la gestion des collections de polices afin d’effectuer les substitutions appropriées grâce à la fonctionnalité de repli. Écrire [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Remarques



```cpp
auto pres = MakeObject<Presentation>();
// Récupération d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// ajout de règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ou
// initialisation d'une nouvelle instance de la collection de règles
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// ajout de règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// et remplacement de la collection existante par la nouvelle dans FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [IFontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)