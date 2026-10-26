---
title: AreEqualImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává rovnost (Equal) plovoucího bodu s aritmetickými typy.
type: docs
weight: 27
url: /cs/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) funkce

Porovnává rovnost (Equal) plovoucích čísel s aritmetickými typy.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ objektu. |
| T2 | RHS typ objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1 | LHS hodnota. |
| rhs | const T2 | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost (Equal) hodnot, kdy jedna nebo obě jsou [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ objektu. |
| T2 | RHS typ objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1\& | LHS hodnota. |
| rhs | const T2\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává rovnost (Equal) neukazatelových typů pomocí poskytnuté metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T\& | LHS hodnota. |
| rhs | const T\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) funkce

Porovnává rovnost (Equal) neukazatelových typů pomocí poskytnuté metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T\& | LHS hodnota. |
| rhs | const T\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává rovnost (Equal) neukazatelových typů pomocí operátoru ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T\& | LHS hodnota. |
| rhs | const T\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkce

Porovnává rovnost (Equal) typu boxable s [SmartPtr](../../system/smartptr/) hodnotami.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T | LHS hodnota. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkce

Porovnává rovnost (Equal) typu boxable s [SmartPtr](../../system/smartptr/) hodnotami.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS hodnota. |
| rhs | T | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) funkce

Porovnává rovnost (Equal) řetězcový literál s [SmartPtr](../../system/smartptr/) hodnotami pomocí unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const char16_t * | LHS hodnota. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) funkce

Porovnává rovnost (Equal) řetězcový literál s [SmartPtr](../../system/smartptr/) hodnotami pomocí unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS hodnota. |
| rhs | const char16_t * | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkce

Porovnává rovnost (Equal) náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T | LHS hodnota. |
| s | std::nullptr_t | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkce

Porovnává rovnost (Equal) náhodného typu s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| rhs | std::nullptr_t | RHS hodnota. |
| s | T | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost (Equal) ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ. |
| T2 | RHS typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1\& | LHS hodnota. |
| rhs | const T2\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost (Equal) ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ. |
| T2 | RHS typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1\& | LHS hodnota. |
| rhs | const T2\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) funkce

Porovnává rovnost (Equal) náhodného typu s [Nullable](../../system/nullable/) hodnotou.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ. |
| T2 | RHS typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T1 | LHS hodnota. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) funkce

Porovnává rovnost (Equal) [Nullable](../../system/nullable/) hodnotu s náhodným typem.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ. |
| T2 | RHS typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS hodnota. |
| rhs | T2 | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) funkce

Porovnává rovnost (Equal) náhodných typů pomocí gtest algoritmů.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ. |
| T2 | RHS typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | T1 | LHS hodnota. |
| rhs | T2 | RHS hodnota. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává rovnost (Equal) dvou [System::String](../../system/string/) hodnot, chrání před voláním členské funkce na nulovém [String](../../system/string/). Šablonová (namísto prostého přetížení, přijímajícího const [String](../../system/string/)&) aby volání smíšených typů – např. řetězcový literál char16_t porovnán s [String](../../system/string/) – nedokázalo odvodit jednotný typ T a byl zcela vyloučen jako kandidát, místo aby soutěžil s obecnou šablonou AreEqualImpl<T1,T2> pomocí selektorového parametru long long/int a vedl ke konfliktu při výběru přetížení.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ, omezen na [System::String](../../system/string/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T\& | LHS hodnota. |
| rhs | const T\& | RHS hodnota. |
| s | long long | Servisní parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## Viz také

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)