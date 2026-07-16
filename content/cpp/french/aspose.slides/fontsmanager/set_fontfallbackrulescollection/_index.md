---
title: set_FontFallBackRulesCollection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la collection d'un utilisateur de règles FontFallBack pour la gestion des collections de polices afin d'assurer des substitutions appropriées grâce à la fonctionnalité de secours. Écrivez IFontFallBackRulesCollection.
type: docs
weight: 40
url: /fr/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallOutRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) méthode


Représente la collection d'un utilisateur de règles FontFallBack pour la gestion des collections de polices afin d'assurer des substitutions appropriées grâce à la fonctionnalité de secours. Écrivez [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Remarques



```cpp
auto pres = MakeObject<Presentation>();
// Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Ajout de règles à la collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ou
// initialisation d'une nouvelle instance de collection de règles
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Ajout de règles à la collection
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