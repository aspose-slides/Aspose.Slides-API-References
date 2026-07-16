---
title: RemoveAt()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la police de secours à l'index spécifié de la liste.
type: docs
weight: 92
url: /fr/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) méthode


Supprime la police de secours à l'index spécifié de la liste.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de la police à supprimer. |
## Remarques



```cpp
// Crée une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Suppression de Tahoma de la liste
newRule->RemoveAt(2);
```


## Voir aussi

* Classe [IFontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)