---
title: HolderInitializer
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette classe est utilisée pour obtenir une référence persistante à l'instance de l'objet, qu'il s'agisse d'un lvalue ou d'un rvalue. Pour obtenir une telle référence, utilisez la méthode 'HoldIfTemporary', qui possède trois surcharges. Deux d'entre elles prennent un rvalue en paramètre et renvoient simplement la référence à celui-ci. La troisième, à l'inverse, prend un lvalue en paramètre, crée une copie de pointeur, puis renvoie la référence à cette copie. De plus, la classe possède la méthode 'Hold' pour retenir la valeur passée inconditionnellement (utilisée pour copier les valeurs de variables locales sur la pile ou leurs références enfants).
type: docs
weight: 1613
url: /fr/system/holderinitializer/
---
## HolderInitializer struct

Cette classe est utilisée pour obtenir une référence persistante à l'instance d'objet, qu'il s'agisse d'un lvalue ou d'un rvalue. Pour obtenir une telle référence, utilisez la méthode `HoldIfTemporary`, qui possède trois surcharges. Deux d'entre elles prennent un rvalue comme paramètre et renvoient simplement la référence à celui-ci. La troisième, à l'inverse, prend un lvalue comme paramètre, crée une copie de pointeur, puis renvoie la référence à cette copie. De plus, la classe possède la méthode `Hold` pour retenir la valeur passée inconditionnellement (utilisée pour copier les valeurs de variables locales sur la pile ou leurs références enfants).

```cpp
template<typename T,bool>class HolderInitializer
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet à retenir. |
| R | Vrai, si T est un type de référence (spécialisation [SmartPtr](../smartptr/) ou type [System::String](../string/)), et que la rétention de références temporaires est réellement requise, faux - sinon. |

## Méthodes

| Méthode | Description |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Copie le lvalue passé dans le holder, puis renvoie la référence du holder. L'appelant doit utiliser cette méthode pour retenir la valeur passée inconditionnellement. |
| [HolderInitializer](./holderinitializer/)(T\&) | Initialise la référence du holder avec celle passée. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Renvoie la référence au rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Renvoie la référence au rvalue (non-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Copie le lvalue passé dans le holder, puis renvoie la référence du holder. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)