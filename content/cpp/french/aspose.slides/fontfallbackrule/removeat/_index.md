---
title: RemoveAt()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Supprime la police FallBack à l'index spécifié de la liste.
type: docs
weight: 131
url: /fr/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) méthode


Supprime la police FallBack à l'index spécifié de la liste.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro de la police à supprimer. |
## Remarques



```cpp
// Crée une règle contenant une liste de polices.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Supprime Tahoma de la liste.
newRule->RemoveAt(2);
```


## Voir aussi

* Classe [FontFallBackRule](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)