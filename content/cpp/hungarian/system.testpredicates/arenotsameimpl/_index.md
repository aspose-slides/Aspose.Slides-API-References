---
title: AreNotSameImpl()
second_title: Aspose.Slides C++ API Referenciája
description: Az Are-not-same okos mutatókat hasonlít össze.
type: docs
weight: 105
url: /hu/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) függvény


Az Are-not-same okos mutatókat hasonlít össze.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | A szolgáltatási paraméter, amely a függvény megvalósításának kiválasztójaként szolgál; a paraméter értéke figyelmen kívül marad |

### Visszatérési érték

gtest-stílusú állítás eredménye.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) függvény


Az Are-not-same nem mutató értékeket hasonlít össze.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

gtest-stílusú állítás eredménye.

## Lásd még

* Struktúra [IsSmartPtr](../../system/issmartptr/)
* Névtér [System::TestPredicates](../)
* Könyvtár [Aspose.Slides](../../)