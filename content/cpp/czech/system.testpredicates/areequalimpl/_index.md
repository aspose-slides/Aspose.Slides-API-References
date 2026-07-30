---
title: AreEqualImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává rovnost plovoucích čísel s aritmetickými typy.
type: docs
weight: 27
url: /cs/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) funkce

Porovnává rovnost s plovoucí desetinnou čárkou a aritmetickými typy.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1 | Hodnota LHS. |
| rhs | const T2 | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost hodnot, z nichž jedna nebo obě jsou [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává rovnost neukazatelových typů pomocí metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T\& | Hodnota LHS. |
| rhs | const T\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) funkce

Porovnává rovnost neukazatelových typů pomocí metody Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T\& | Hodnota LHS. |
| rhs | const T\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funkce

Porovnává rovnost neukazatelových typů pomocí operátoru ==.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T\& | Hodnota LHS. |
| rhs | const T\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funkce

Porovnává rovnost boxovatelných typů s hodnotami [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T | Hodnota LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funkce

Porovnává rovnost boxovatelných typů s hodnotami [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota LHS. |
| rhs | T | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) funkce

Porovnává řetězcový literál s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const char16_t * | Hodnota LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) funkce

Porovnává řetězcový literál s hodnotami [SmartPtr](../../system/smartptr/) pomocí rozbalení.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Hodnota LHS. |
| rhs | const char16_t * | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funkce

Porovnává náhodný typ s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T | Hodnota LHS. |
| s | std::nullptr_t | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funkce

Porovnává náhodný typ s nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ [Object](../../system/object/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| rhs | std::nullptr_t | Hodnota RHS. |
| s | T | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává rovnost ukazatelových typů.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) funkce

Porovnává náhodný typ s hodnotou [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T1 | Hodnota LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) funkce

Porovnává hodnotu [Nullable](../../system/nullable/) s náhodným typem.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Hodnota LHS. |
| rhs | T2 | Hodnota RHS. |
| s | long long | Služební parametr sloužící jako výběr implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) funkce

Porovnává náhodné typy pomocí algoritmů gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ LHS. |
| T2 | Typ RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | T1 | Hodnota LHS. |
| rhs | T2 | Hodnota RHS. |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## Viz také

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [Object](../../system/object/)
* Třída [Stream](../../system.io/stream/)
* Třída [Nullable](../../system/nullable/)
* Struktura [IsSmartPtr](../../system/issmartptr/)
* Struktura [IsBoxable](../../system/isboxable/)
* Struktura [IsStringByteSequence](../../system/isstringbytesequence/)
* Struktura [IsNullable](../../system/isnullable/)
* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)