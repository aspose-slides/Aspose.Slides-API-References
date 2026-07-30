---
title: AreNotSameImpl()
second_title: Riferimento API Aspose.Slides per C++
description: Confronta smart pointer per verificarne la non uguaglianza.
type: docs
weight: 105
url: /it/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-not-same-compares puntatori intelligenti.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

gtest-styled assertion result.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

Are-not-same-compares valori non puntatori.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |

### Valore di ritorno

gtest-styled assertion result.

## Vedi anche

* Struttura [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)