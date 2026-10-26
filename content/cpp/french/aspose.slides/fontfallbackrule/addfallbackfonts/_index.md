---
title: AddFallBackFonts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une ou plusieurs nouvelles polices à la liste des polices FallBack.
type: docs
weight: 79
url: /fr/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) méthode


Ajoute une ou plusieurs nouvelles polices à la liste des polices FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nom ou noms de la police (délimités par une virgule) pour FallBack |
## Remarques



```cpp
// Crée une nouvelle instance de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Ajoute une deuxième police à la règle
newRule->AddFallBackFonts(u"MS Gothic");
//Ajoute une troisième et une quatrième police à la règle
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) méthode


Ajoute de nouvelles polices à la liste des polices FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nom ou noms de la police (délimités par une virgule) pour FallBack |
## Remarques



```cpp
//Créer une nouvelle instance de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Ajout de trois autres polices à la règle
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)