---
title: operator()()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleichsfunktion für Typen, bei denen der Operator < verfügbar ist.
type: docs
weight: 27
url: /de/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q&, const Q&) const Methode

[Comparison](../../../system/comparison/) Funktion für Typen mit operator < verfügbar.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ, der verglichen wird; Vorlage für die Verfügbarkeit der Typkonvertierung. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const Q& | Erster zu vergleichender Wert. |
| y | const Q& | Zweiter zu vergleichender Wert. |

### Rückgabewert

Wahr, wenn **x** als kleiner als **y** betrachtet wird, andernfalls falsch.

## ComparerAdapter::operator()(const Q&, const Q&) const Methode

[Comparison](../../../system/comparison/) Funktion für Typen, bei denen operator < nicht verfügbar ist.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ, der verglichen wird; Vorlage für die Verfügbarkeit der Typkonvertierung. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const Q& | Erster zu vergleichender Wert. |
| y | const Q& | Zweiter zu vergleichender Wert. |

### Rückgabewert

Wahr, wenn der Comparator gesetzt ist und **x** als kleiner als **y** betrachtet wird, andernfalls falsch.

## Siehe auch

* Struktur [ComparerAdapter](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)