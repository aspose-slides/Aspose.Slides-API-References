---
title: Equals()
second_title: Aspose.Slides dla C++ – referencja API
description: Określa równość podanej wartości przy użyciu operatora ==().
type: docs
weight: 66
url: /pl/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) funkcja


Określa równość podanej wartości przy użyciu [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Typ | typ wartości porównywanych |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value1 | T | Pierwszy operand |
| value2 | T | Drugi operand |

### Wartość zwracana

true jeśli podana wartość jest równa zgodnie z [operator==()](../../system/operator_equal_equal/), w przeciwnym razie - false

## System::BoxedValueDetail::Equals(T, T) funkcja


Określa równość podanej wartości przy użyciu metody [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Typ | typ wartości porównywanych |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value1 | T | Pierwszy operand |
| value2 | T | Drugi operand |

### Wartość zwracana

true jeśli podana wartość jest równa zgodnie z metodą [Equals()](./), w przeciwnym razie - false

## Zobacz także

* Przestrzeń nazw [System::BoxedValueDetail](../)
* Biblioteka [Aspose.Slides](../../)