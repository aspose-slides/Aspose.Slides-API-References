---
title: operator()()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fonction de comparaison pour les types dont l'opérateur < est disponible.
type: docs
weight: 27
url: /fr/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const méthode

[Comparison](../../../system/comparison/) fonction pour les types dont l'opérateur < est disponible.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer ; modèle pour la disponibilité de la conversion de type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const Q\& | Première valeur à comparer. |
| y | const Q\& | Deuxième valeur à comparer. |

### Valeur de retour

Vrai si **x** est considéré comme inférieur à **y**, false sinon.

## ComparerAdapter::operator()(const Q\&, const Q\&) const méthode

[Comparison](../../../system/comparison/) fonction pour les types dont l'opérateur < n'est pas disponible.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer ; modèle pour la disponibilité de la conversion de type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const Q\& | Première valeur à comparer. |
| y | const Q\& | Deuxième valeur à comparer. |

### Valeur de retour

Vrai si le comparateur est défini et que **x** est considéré comme inférieur à **y**, false sinon.

## Voir aussi

* Structure [ComparerAdapter](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)