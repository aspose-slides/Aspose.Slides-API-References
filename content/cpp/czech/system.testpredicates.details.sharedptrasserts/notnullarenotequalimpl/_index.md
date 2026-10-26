---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává nerovnost polí nebo seznamů.
type: docs
weight: 105
url: /cs/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává nerovnost polí nebo seznamů.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ kontejneru. |
| T2 | RHS typ kontejneru. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1\& | LHS hodnota. |
| rhs | const T2\& | RHS hodnota. |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru se ignoruje |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Porovnává nerovnost instancí IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | LHS typ prvku. |
| T2 | RHS typ prvku. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | LHS výraz. |
| rhs_expr | const char * | RHS výraz. |
| lhs | const T1\& | LHS hodnota. |
| rhs | const T2\& | RHS hodnota. |
| s | long long | Parametr služby, který slouží jako selektor implementace funkce; hodnota parametru se ignoruje |

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) funkce

Porovnává nerovnost neznámých typů pomocí metody Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
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

### Návratová hodnota

Výsledek aserce ve stylu gtest.

## Viz také

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struktura [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Jmenný prostor [System::TestPredicates::Details::SharedPtrAsserts](../)
* Knihovna [Aspose.Slides](../../)