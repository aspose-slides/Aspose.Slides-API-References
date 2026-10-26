---
title: Equals()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza a megadott érték egyenlőségét az operator==() használatával.
type: docs
weight: 66
url: /hu/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) függvény

Meghatározza a megadott érték egyenlőségét a(z) [operator==()](../../system/operator_equal_equal/) segítségével.

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| A | az összehasonlított értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value1 | T | az első összehasonlítandó |
| value2 | T | a második összehasonlítandó |

### Visszatérési érték

True, ha a megadott értékek egyenlőek, ahogy azt a(z) [operator==()](../../system/operator_equal_equal/) határozza meg, egyébként - false

## System::BoxedValueDetail::Equals(T, T) függvény

Meghatározza a megadott érték egyenlőségét a(z) [System::Object::Equals()](../../system/object/equals/) metódus segítségével.

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| A | az összehasonlított értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value1 | T | az első összehasonlítandó |
| value2 | T | a második összehasonlítandó |

### Visszatérési érték

True, ha a megadott értékek egyenlőek, ahogy azt a(z) [Equals()](./) metódus határozza meg, egyébként - false

## Lásd még

* Namespace [System::BoxedValueDetail](../)
* Library [Aspose.Slides](../../)