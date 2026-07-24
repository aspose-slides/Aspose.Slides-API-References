---
title: AreSameImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Are-same vergleicht Smart-Pointer.
type: docs
weight: 79
url: /de/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion


Are-same vergleicht Smart-Pointer.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Selektor der Implementierung der Funktion dient; der Wert des Parameters wird ignoriert |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion


Are-same vergleicht Ausnahmen.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Selektor der Implementierung der Funktion dient; der Wert des Parameters wird ignoriert |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) Funktion


Are-same vergleicht Nicht-Pointer-Werte.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |

### Rückgabewert

gtest-stilisiertes Assertion-Ergebnis.

## Siehe auch

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namensraum [System::TestPredicates](../)
* Library [Aspose.Slides](../../)