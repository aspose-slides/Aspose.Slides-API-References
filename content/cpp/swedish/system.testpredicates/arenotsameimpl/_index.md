---
title: AreNotSameImpl()
second_title: Aspose.Slides för C++ API-referens
description: Are-not-same jämför smarta pekare.
type: docs
weight: 105
url: /sv/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funktion


Are-not-same jämför smarta pekare.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objekttyp. |
| T2 | RHS-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |
| s | long long | En tjänsteparameter som fungerar som en selektor för implementeringen av funktionen; parametervärdet ignoreras |

### Returvärde

gtest-stylat påståenderesultat.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) funktion


Are-not-same jämför icke-pekarevärden.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS-objekttyp. |
| T2 | RHS-objekttyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS-uttryck. |
| rhs_expr | const char * | RHS-uttryck. |
| lhs | const T1\& | LHS-värde. |
| rhs | const T2\& | RHS-värde. |

### Returvärde

gtest-stylat påståenderesultat.

## Se även

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)