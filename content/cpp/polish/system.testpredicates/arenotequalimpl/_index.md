---
title: AreNotEqualImpl()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Porównanie nierówności sprawdza wartości, z których jedna lub obie są typu Decimal.
type: docs
weight: 53
url: /pl/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja

Porównanie nierówności sprawdza wartości, z których jedna lub obie są [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ obiektu LHS. |
| T2 | typ obiektu RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1\& | wartość LHS. |
| rhs | const T2\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja

Porównanie nierówności porównuje dwie wartości [System::String](../../system/string/), chroniąc przed wywołaniem funkcji członkowskiej na pustym [String](../../system/string/). Szablonowany z tych samych powodów wykluczenia opartego na dedukcji co przeciążenie AreEqualImpl [String](../../system/string/) powyżej.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/), ograniczony do [System::String](../../system/string/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja

Porównanie nierówności porównuje typy nie-wskaźnikowe przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) funkcja

Porównanie nierówności porównuje typy nie-wskaźnikowe przy użyciu dostarczonej metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkcja

Porównanie nierówności porównuje typy nie-wskaźnikowe przy użyciu operatora !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T\& | wartość LHS. |
| rhs | const T\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkcja

Porównanie nierówności porównuje typy możliwe do spakowania z wartościami [SmartPtr](../../system/smartptr/) przy użyciu odpakowywania.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T | wartość LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkcja

Porównanie nierówności porównuje typy możliwe do spakowania z wartościami [SmartPtr](../../system/smartptr/) przy użyciu odpakowywania.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | wartość LHS. |
| rhs | T | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkcja

Porównanie nierówności porównuje losowy typ z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T | wartość LHS. |
| s | std::nullptr_t | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkcja

Porównanie nierówności porównuje losowy typ z nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| rhs | std::nullptr_t | wartość RHS. |
| s | T | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkcja

Porównanie równości porównuje typy wskaźnikowe.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | const T1\& | wartość LHS. |
| rhs | const T2\& | wartość RHS. |
| s | long long | Parametr serwisowy służący jako selektor implementacji funkcji; wartość parametru jest ignorowana |

### Wartość zwracana

wynik asercji w stylu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) funkcja

Porównanie równości porównuje losowe typy przy użyciu algorytmów gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | typ LHS. |
| T2 | typ RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs_expr | const char * | wyrażenie LHS. |
| rhs_expr | const char * | wyrażenie RHS. |
| lhs | T1 | wartość LHS. |
| rhs | T2 | wartość RHS. |

### Wartość zwracana

wynik asercji w stylu gtest.

## Zobacz także

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)