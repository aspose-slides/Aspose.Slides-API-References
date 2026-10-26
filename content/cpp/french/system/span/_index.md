---
title: Span
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une région contiguë de mémoire arbitraire similaire à std::span de C++20."
type: docs
weight: 1236
url: /fr/system/span/
---
## Span classe

Représente une région contiguë de mémoire arbitraire similaire à std::span de C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments dans le span. Cette classe offre une façon sécurisée de travailler avec des séquences contiguës d'objets. Elle peut être utilisée pour encapsuler des tableaux, des tableaux empilés ou des pointeurs bruts tout en conservant la vérification des limites. Le [Span](./) ne possède pas la mémoire à laquelle il pointe - il ne s'agit que d'une vue sur la mémoire existante. |

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Clear](./clear/)() const | Efface le contenu du span en définissant tous les éléments à leur valeur par défaut. |
| void [Fill](./fill/)(const T\&) const | Remplit le span avec la valeur spécifiée. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Convertit un tableau en [Span](./). |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)