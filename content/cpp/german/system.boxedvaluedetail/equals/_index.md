---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt die Gleichheit des angegebenen Werts mithilfe des Operators ==().
type: docs
weight: 66
url: /de/system.boxedvalueddetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) Funktion


Bestimmt die Gleichheit des angegebenen Werts mithilfe von [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| The | Typ der verglichenen Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value1 | T | Der erste Vergleichswert |
| value2 | T | Der zweite Vergleichswert |

### Rückgabewert

True, wenn der angegebene Wert gleich ist, wie von [operator==()](../../system/operator_equal_equal/) bestimmt, andernfalls - false

## System::BoxedValueDetail::Equals(T, T) Funktion


Bestimmt die Gleichheit des angegebenen Werts mit der Methode [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| The | Typ der verglichenen Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value1 | T | Der erste Vergleichswert |
| value2 | T | Der zweite Vergleichswert |

### Rückgabewert

True, wenn der angegebene Wert gleich ist, wie von [Equals()](./) bestimmt, andernfalls - false

## Siehe auch

* Namensraum [System::BoxedValueDetail](../)
* Bibliothek [Aspose.Slides](../../)