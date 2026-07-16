---
title: Remove()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la première occurrence d’une police FallBack spécifique de la liste.
type: docs
weight: 118
url: /fr/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) méthode


Supprime la première occurrence d’une police FallBack spécifique de la liste.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Le nom de la police à supprimer de la liste. |
## Remarques



```cpp
// Créer une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Supprimer Tahoma de la liste.
newRule->Remove(u"Tahoma");
```


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)