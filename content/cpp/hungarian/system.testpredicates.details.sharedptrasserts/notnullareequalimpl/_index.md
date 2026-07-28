---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides C++ API Referencia
description: Egyenlőség szerint hasonlítja össze a tömböket vagy listákat.
type: docs
weight: 40
url: /hu/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény

Egyenlőség szerint hasonlítja össze a tömböket vagy listákat.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS konténer típusa. |
| T2 | RHS konténer típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |
| s | long long | Szolgáltatási paraméter, amely a függvény implementációjának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény

Egyenlőség szerint hasonlítja össze az IEnumerable példányokat.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS elem típusa. |
| T2 | RHS elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |
| s | long long | Szolgáltatási paraméter, amely a függvény implementációjának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül van hagyva |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) függvény

Egyenlőség szerint hasonlítja össze az ismeretlen típusokat az Equals metódus használatával.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | LHS objektum típusa. |
| T2 | RHS objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhs_expr | const char * | LHS kifejezés. |
| rhs_expr | const char * | RHS kifejezés. |
| lhs | const T1\& | LHS érték. |
| rhs | const T2\& | RHS érték. |

### Visszatérési érték

gtest-stílusú állítási eredmény.

## Lásd még

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)