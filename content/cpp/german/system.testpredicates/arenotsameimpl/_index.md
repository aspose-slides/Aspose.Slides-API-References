---
title: AreNotSameImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Are-not-same vergleicht Smart-Pointer.
type: docs
weight: 105
url: /de/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion


Are-not-same vergleicht Smart-Pointer.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS Objekttyp. |
| T2 | RHS Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS Ausdruck. |
| rhs_expr | const char * | RHS Ausdruck. |
| lhs | const T1\& | LHS Wert. |
| rhs | const T2\& | RHS Wert. |
| s | long long | Ein Service-Parameter, der als Selektor für die Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-stiltes Assertionsergebnis.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) Funktion


Are-not-same vergleicht Werte ohne Zeiger.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS Objekttyp. |
| T2 | RHS Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS Ausdruck. |
| rhs_expr | const char * | RHS Ausdruck. |
| lhs | const T1\& | LHS Wert. |
| rhs | const T2\& | RHS Wert. |

### Rückgabewert

gtest-stiltes Assertionsergebnis.

## Siehe auch

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)