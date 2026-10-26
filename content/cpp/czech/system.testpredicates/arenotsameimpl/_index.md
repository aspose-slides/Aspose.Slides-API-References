---
title: AreNotSameImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Are-not-same porovnává chytré ukazatele.
type: docs
weight: 105
url: /cs/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funkce

Are-not-same porovnává chytré ukazatele.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu levé strany. |
| T2 | Typ objektu pravé strany. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz levé strany. |
| rhs_expr | const char * | Výraz pravé strany. |
| lhs | const T1\& | Hodnota levé strany. |
| rhs | const T2\& | Hodnota pravé strany. |
| s | long long | Služební parametr, který slouží jako výběr implementace funkce; hodnota parametru se ignoruje |

### Návratová hodnota

výsledek aserce ve stylu gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) funkce

Are-not-same porovnává neukazatelové hodnoty.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ objektu levé strany. |
| T2 | Typ objektu pravé strany. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs_expr | const char * | Výraz levé strany. |
| rhs_expr | const char * | Výraz pravé strany. |
| lhs | const T1\& | Hodnota levé strany. |
| rhs | const T2\& | Hodnota pravé strany. |

### Návratová hodnota

výsledek aserce ve stylu gtest.

## Viz také

* Struktura [IsSmartPtr](../../system/issmartptr/)
* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)