---
title: AreSameImpl()
second_title: Aspose.Slides för C++ API-referens
description: Are-same jämför smartpekare.
type: docs
weight: 79
url: /sv/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Are-same-compares smartpekare.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | En serviceparameter som fungerar som en väljare av implementationen av funktionen; parametrens värde ignoreras |

### Returvärde

gtest-stilat assertionsresultat.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Are-same-compares undantag.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | En serviceparameter som fungerar som en väljare av implementationen av funktionen; parametrens värde ignoreras |

### Returvärde

gtest-stilat assertionsresultat.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) funktion


Are-same-compares icke-pekarevärden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Returvärde

gtest-stilat assertionsresultat.

## Se även

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)