---
title: AreSameImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Are-same vergelijkt slimme pointers.
type: docs
weight: 79
url: /nl/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) functie


Are-same vergelijkt slimme pointers.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Retourwaarde

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) functie


Are-same vergelijkt uitzonderingen.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Retourwaarde

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) functie


Are-same vergelijkt niet-pointerwaarden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Retourwaarde

gtest-styled assertion result.

## Zie ook

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)