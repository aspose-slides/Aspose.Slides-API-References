---
title: AreNotSameImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Are-not-same vergelijkt slimme pointers.
type: docs
weight: 105
url: /nl/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) functie


Are-not-same vergelijkt slimme pointers.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS uitdrukking. |
| rhs_expr | const char * | RHS uitdrukking. |
| lhs | const T1\& | LHS waarde. |
| rhs | const T2\& | RHS waarde. |
| s | long long | Een service-parameter die fungeert als selector van de implementatie van de functie; de waarde van de parameter wordt genegeerd |

### Retourwaarde

gtest-styled assertion result.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) functie


Are-not-same vergelijkt niet-pointer waarden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS uitdrukking. |
| rhs_expr | const char * | RHS uitdrukking. |
| lhs | const T1\& | LHS waarde. |
| rhs | const T2\& | RHS waarde. |

### Retourwaarde

gtest-styled assertion result.

## Zie ook

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)