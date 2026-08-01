---
title: operator()()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt waardetypen die de IComparable interface implementeren.
type: docs
weight: 1
url: /nl/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const methode

Vergelijkt waardetypen die de [IComparable](../../../system/icomparable/) interface implementeren.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const Q\& | LHS-waarde. |
| b | const Q\& | RHS-waarde. |

### Retourwaarde

True als **a** wordt beschouwd als kleiner dan **b**, false anders.

## ComparerType::operator()(const Q\&, const Q\&) const methode

Vergelijkt primitieve waardetypen en objecten die de [IComparable](../../../system/icomparable/) interface niet implementeren.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const Q\& | LHS-waarde. |
| b | const Q\& | RHS-waarde. |

### Retourwaarde

True als **a** wordt beschouwd als kleiner dan **b**, false anders.

## ComparerType::operator()(const Q\&, const Q\&) const methode

Vergelijkt zwevende-kommagetallen.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const Q\& | LHS-waarde. |
| b | const Q\& | RHS-waarde. |

### Retourwaarde

True als **a** wordt beschouwd als kleiner dan **b**, false anders.

## Zie ook

* Klasse [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Naamruimte [System::Collections::Generic::Details](../../)
* Bibliotheek [Aspose.Slides](../../../)