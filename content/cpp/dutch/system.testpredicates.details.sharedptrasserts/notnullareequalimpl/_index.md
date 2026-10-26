---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt arrays of lijsten op gelijkheid.
type: docs
weight: 40
url: /nl/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) functie

Vergelijkt arrays of lijsten op gelijkheid.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS containertype. |
| T2 | RHS containertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressie. |
| rhs_expr | const char * | RHS expressie. |
| lhs | const T1\& | LHS waarde. |
| rhs | const T2\& | RHS waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Returnwaarde

gtest-stijl assertieresultaat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) functie

Vergelijkt IEnumerable-instanties op gelijkheid.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS elementtype. |
| T2 | RHS elementtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressie. |
| rhs_expr | const char * | RHS expressie. |
| lhs | const T1\& | LHS waarde. |
| rhs | const T2\& | RHS waarde. |
| s | long long | Een serviceparameter die dient als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Returnwaarde

gtest-stijl assertieresultaat.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) functie

Vergelijkt onbekende types met behulp van de Equals-methode.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS objecttype. |
| T2 | RHS objecttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressie. |
| rhs_expr | const char * | RHS expressie. |
| lhs | const T1\& | LHS waarde. |
| rhs | const T2\& | RHS waarde. |

### Returnwaarde

gtest-stijl assertieresultaat.

## Zie ook

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)