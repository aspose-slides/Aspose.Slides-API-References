---
title: FontFallBackRulesCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente la collection de règles FontFallBack dun utilisateur pour la gestion des collections de polices pour les substitutions appropriées par la fonctionnalité de secours Lecture/écritureIFontFallBackRulesCollectionaspose.slides/ifontfallbackrulescollection .
type: docs
weight: 10
url: /fr/aspose.slides/ifontsmanager/fontfallbackrulescollection/
---
## IFontsManager.FontFallBackRulesCollection property

Représente la collection de règles FontFallBack d'un utilisateur pour la gestion des collections de polices pour les substitutions appropriées par la fonctionnalité de secours Lecture/écriture[`IFontFallBackRulesCollection`](../../ifontfallbackrulescollection) .

```csharp
public IFontFallBackRulesCollection FontFallBackRulesCollection { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    // Obtention d'une collection de règles vides ou préinitialisées depuis FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    // ajout de règles à la collection
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));

    // ou 
    // initialisation de la nouvelle instance de collection de règles
    IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();

    // ajout de règles à la collection
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));

    // et remplacement de la collection existante par la nouvelle dans FontsManager 
    pres.FontsManager.FontFallBackRulesCollection = rulesList;
}
```

### Voir également

* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* interface [IFontsManager](../../ifontsmanager)
* espace de noms [Aspose.Slides](../../ifontsmanager)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
