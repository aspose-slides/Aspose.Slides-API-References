---
title: AddFallBackFonts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une ou plusieurs nouvelles polices à la liste des polices FallBack.
type: docs
weight: 40
url: /fr/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) méthode


Ajoute une ou plusieurs nouvelles polices à la liste des polices FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nom ou noms de la police (délimités par des virgules) pour FallBack |
## Remarques



```cpp
//Créer une nouvelle instance de FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Ajouter une deuxième police à la règle
newRule->AddFallBackFonts(u"MS Gothic");
//Ajouter une troisième et une quatrième police à la règle
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) méthode


Ajoute de nouvelles polices à la liste des polices FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nom ou noms de la police (délimités par des virgules) pour FallBack |
## Remarques



```cpp
//Créer une nouvelle instance de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Ajouter trois autres polices à la règle
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)