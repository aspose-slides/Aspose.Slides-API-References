---
title: PrintToStringImpl()
second_title: Aspose.Slides C++ API referencia
description: "Kiírja a System::Object alosztályt karakterláncba a ToString() metódus segítségével."
type: docs
weight: 14
url: /hu/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) függvény

Nyomtatja a [System::Object](../../system/object/) alosztályt karakterláncra a ToString() metódus használatával.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Végleges osztálytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | A nyomtatandó objektumra mutató mutató. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak vagy "nullptr", ha **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) függvény

Nyomtatja a [System::Object](../../system/object/) alosztályt karakterláncra a ToString() metódus használatával.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Végleges osztálytípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | A nyomtatandó objektumra mutató mutató. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak vagy "nullptr", ha **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) függvény

Nyomtatja az objektumot karakterláncra a ToString() metódus használatával.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) függvény

Nyomtatja az objektumot karakterláncra a PrintTo metódus használatával.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) függvény

Nyomtatja az objektumot karakterláncra a PrintTo metódus használatával.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) függvény

Nyomtatja a párost karakterláncra.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első pár típusargumentuma. |
| T2 | A második pár típusargumentuma. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

Az első és a második pár komponenseinek közös karakterlánc-ábrázolása.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) függvény

Nyomtatja a párost karakterláncra.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az első pár típusargumentuma. |
| T2 | A második pár típusargumentuma. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

Az első és a második pár komponenseinek közös karakterlánc-ábrázolása.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) függvény

Nyomtatja az STL-stílusú tárolókat karakterláncra azok elemeinek nyomtatásával (legfeljebb 32 elem).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | long long | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

A tárolt elemek közös karakterlánc-ábrázolása.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) függvény

Nyomtatja a többi típust karakterláncra a gtest által biztosított függvények használatával.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a nyomtatáshoz. |
| s | int | Szolgáltató paraméter, amely a típusa alapján választja ki a függvény túlterhelését; a paraméter értéke figyelmen kívül marad. |

### Visszatérési érték

[String](../../system/string/) ábrázolása az átadott objektumnak.

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)