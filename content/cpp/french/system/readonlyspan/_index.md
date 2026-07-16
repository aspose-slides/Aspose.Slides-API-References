---
title: ReadOnlySpan
second_title: Référence de l'API Aspose.Slides pour C++
description: À utiliser dans la classe Span.
type: docs
weight: 1184
url: /fr/system/readonlyspan/
---
## ReadOnlySpan classe

À utiliser dans la classe [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du span. Cette classe fournit un moyen sûr au niveau du type de travailler avec des séquences contiguës d'objets en lecture seule. Elle peut être utilisée pour encapsuler des tableaux, des tableaux empilés ou des pointeurs bruts tout en conservant la vérification des limites. Le [ReadOnlySpan](./) ne possède pas la mémoire à laquelle il pointe - il s'agit simplement d'une vue sur la mémoire existante. |

## Méthodes

| Méthode | Description |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Construit un span en lecture seule à partir d'un span régulier. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Convertit un tableau en [ReadOnlySpan](./). |

## Remarques

Représente une région contiguë en lecture seule de mémoire arbitraire.

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)