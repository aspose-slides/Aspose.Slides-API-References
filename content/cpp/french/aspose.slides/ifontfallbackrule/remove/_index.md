---
title: Remove()
second_title: Référence API Aspose.Slides pour C++
description: Supprime la première occurrence d'une police FallBack spécifique de la liste.
type: docs
weight: 79
url: /fr/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) méthode

Supprime la première occurrence d'une police FallBack spécifique de la liste.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Le nom de la police à supprimer de la liste. |
## Remarques

```cpp
// Crée une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Suppression de Tahoma de la liste
newRule->Remove(u"Tahoma");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)