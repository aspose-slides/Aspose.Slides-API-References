---
title: AreSameImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Are-same porovnává chytré ukazatele.
type: docs
weight: 79
url: /cs/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Are-same-compares chytré ukazatele.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |
| s | long long | Služební parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

gtest-styled výsledek tvrzení.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Are-same-compares výjimky.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |
| s | long long | Služební parametr, který slouží jako selektor implementace funkce; hodnota parametru je ignorována |

### Návratová hodnota

gtest-styled výsledek tvrzení.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) funkce

Are-same-compares neukazatelové hodnoty.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu LHS. |
| T2 | Typ objektu RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz LHS. |
| rhs_expr | const char * | Výraz RHS. |
| lhs | const T1\& | Hodnota LHS. |
| rhs | const T2\& | Hodnota RHS. |

### Návratová hodnota

gtest-styled výsledek tvrzení.

## Viz také

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)