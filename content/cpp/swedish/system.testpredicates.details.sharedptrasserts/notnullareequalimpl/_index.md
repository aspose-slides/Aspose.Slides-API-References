---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides för C++ API-referens
description: Jämför lika arrayer eller listor.
type: docs
weight: 40
url: /sv/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Jämför lika arrayer eller listor.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-behållartyp. |
| T2 | RHS-behållartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stilat påståenderesultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion

Jämför lika IEnumerable-instanser.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-elementtyp. |
| T2 | RHS-elementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En serviceparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stilat påståenderesultat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) funktion

Jämför lika okända typer med Equals-metoden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objektstyp. |
| T2 | RHS-objektstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |

### Returvärde

gtest-stilat påståenderesultat.

## Se även

* Typdefinition [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typdefinition [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struktur [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namnområde [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliotek [Aspose.Slides](../../)