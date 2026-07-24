---
title: operator()()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Wertetypen, die das Interface IComparable implementieren.
type: docs
weight: 1
url: /de/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const Methode

Vergleicht Wertetypen, die das Interface [IComparable](../../../system/icomparable/) implementieren.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ zum Vergleichen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const Q\& | LHS-Wert. |
| b | const Q\& | RHS-Wert. |

### Rückgabewert

Wahr, wenn **a** als kleiner als **b** betrachtet wird, sonst falsch.

## ComparerType::operator()(const Q\&, const Q\&) const Methode

Vergleicht primitive Wertetypen und Objekte, die das Interface [IComparable](../../../system/icomparable/) nicht implementieren.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ zum Vergleichen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const Q\& | LHS-Wert. |
| b | const Q\& | RHS-Wert. |

### Rückgabewert

Wahr, wenn **a** als kleiner als **b** betrachtet wird, sonst falsch.

## ComparerType::operator()(const Q\&, const Q\&) const Methode

Vergleicht Gleitkommatypen.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ zum Vergleichen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const Q\& | LHS-Wert. |
| b | const Q\& | RHS-Wert. |

### Rückgabewert

Wahr, wenn **a** als kleiner als **b** betrachtet wird, sonst falsch.

## Siehe auch

* Klasse [IComparable](../../../system/icomparable/)
* Struktur [has_method_compareto](../../has_method_compareto/)
* Struktur [ComparerType](../)
* Namensraum [System::Collections::Generic::Details](../../)
* Bibliothek [Aspose.Slides](../../../)