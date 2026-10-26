---
title: Equals()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje rovnost zadané hodnoty pomocí operátoru ==().
type: docs
weight: 66
url: /cs/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) funkce

Určuje rovnost zadané hodnoty pomocí [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| The | typ hodnot, které se porovnávají |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | první porovnávaná hodnota |
| value2 | T | druhá porovnávaná hodnota |

### Návratová hodnota

True, pokud jsou zadané hodnoty rovny podle [operator==()](../../system/operator_equal_equal/), jinak - false

## System::BoxedValueDetail::Equals(T, T) funkce

Určuje rovnost zadané hodnoty pomocí metody [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parametry šablony

| Parameter | Description |
| --- | --- |
| The | typ hodnot, které se porovnávají |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | první porovnávaná hodnota |
| value2 | T | druhá porovnávaná hodnota |

### Návratová hodnota

True, pokud jsou zadané hodnoty rovny podle metody [Equals()](./), jinak - false

## Viz také

* jmenný prostor [System::BoxedValueDetail](../)
* knihovna [Aspose.Slides](../../)