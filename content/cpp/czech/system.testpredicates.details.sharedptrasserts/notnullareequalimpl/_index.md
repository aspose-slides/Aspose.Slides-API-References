---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává pole nebo seznamy.
type: docs
weight: 40
url: /cs/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce


Porovnává pole nebo seznamy.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru levé strany. |
| T2 | Typ kontejneru pravé strany. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz levé strany. |
| rhs_expr | const char * | Výraz pravé strany. |
| lhs | const T1\& | Hodnota levé strany. |
| rhs | const T2\& | Hodnota pravé strany. |
| s | long long | Služební parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce


Porovnává instance IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ prvku levé strany. |
| T2 | Typ prvku pravé strany. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz levé strany. |
| rhs_expr | const char * | Výraz pravé strany. |
| lhs | const T1\& | Hodnota levé strany. |
| rhs | const T2\& | Hodnota pravé strany. |
| s | long long | Služební parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) funkce


Porovnává neznámé typy pomocí metody Equals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu levé strany. |
| T2 | Typ objektu pravé strany. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz levé strany. |
| rhs_expr | const char * | Výraz pravé strany. |
| lhs | const T1\& | Hodnota levé strany. |
| rhs | const T2\& | Hodnota pravé strany. |

### Návratová hodnota

gtest-styled assertion result.

## Viz také

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* jmenný prostor [System::TestPredicates::Details::SharedPtrAsserts](../)
* Knihovna [Aspose.Slides](../../)