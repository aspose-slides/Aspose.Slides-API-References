---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Icke lika jämförelse för arrayer eller listor.
type: docs
weight: 105
url: /sv/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Jämförelse för icke lika jämför arrayer eller listor.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-containertyp. |
| T2 | RHS-containertyp. |

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Jämförelse för icke lika jämför IEnumerable-instanser.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-elementtyp. |
| T2 | RHS-elementtyp. |

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-styled assertion result.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) funktion


Jämförelse för icke lika jämför okända typer med Eqauals-metoden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objektstyp. |
| T2 | RHS-objektstyp. |

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |

### Returvärde

gtest-styled assertion result.

## Se även

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)