---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Nicht-gleich vergleicht Arrays oder Listen.
type: docs
weight: 105
url: /de/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Nicht-gleich vergleicht Arrays oder Listen.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Containertyp. |
| T2 | RHS-Containertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Selektor der Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-gestyltes Assertionsergebnis.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) Funktion

Nicht-gleich vergleicht IEnumerable-Instanzen.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Elementtyp. |
| T2 | RHS-Elementtyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |
| s | long long | Ein Dienstparameter, der als Selektor der Implementierung der Funktion dient; der Wert des Parameters wird ignoriert. |

### Rückgabewert

gtest-gestyltes Assertionsergebnis.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) Funktion

Nicht-gleich vergleicht unbekannte Typen mit der Eqauals-Methode.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | LHS-Objekttyp. |
| T2 | RHS-Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs_expr | const char * | LHS-Ausdruck. |
| rhs_expr | const char * | RHS-Ausdruck. |
| lhs | const T1\& | LHS-Wert. |
| rhs | const T2\& | RHS-Wert. |

### Rückgabewert

gtest-gestyltes Assertionsergebnis.

## Siehe auch

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struktur [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namensraum [System::TestPredicates::Details::SharedPtrAsserts](../)
* Bibliothek [Aspose.Slides](../../)