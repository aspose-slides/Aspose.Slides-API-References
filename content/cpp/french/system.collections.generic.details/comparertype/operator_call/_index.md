---
title: operator()()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les types de valeur implémentant l'interface IComparable.
type: docs
weight: 1
url: /fr/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const méthode

Compare les types de valeur implémentant l'interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const Q\& | Valeur LHS. |
| b | const Q\& | Valeur RHS. |

### Valeur de retour

True si **a** est considéré comme inférieur à **b**, false sinon.

## ComparerType::operator()(const Q\&, const Q\&) const méthode

Compare les types de valeur primitifs et les objets ne implémentant pas l'interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const Q\& | Valeur LHS. |
| b | const Q\& | Valeur RHS. |

### Valeur de retour

True si **a** est considéré comme inférieur à **b**, false sinon.

## ComparerType::operator()(const Q\&, const Q\&) const méthode

Compare les types à virgule flottante.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const Q\& | Valeur LHS. |
| b | const Q\& | Valeur RHS. |

### Valeur de retour

True si **a** est considéré comme inférieur à **b**, false sinon.

## Voir aussi

* Classe [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Espace de noms [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)