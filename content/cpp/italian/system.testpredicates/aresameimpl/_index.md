---
title: AreSameImpl()
second_title: Riferimento API Aspose.Slides per C++
description: Are-same confronta puntatori intelligenti.
type: docs
weight: 79
url: /it/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funzione

Are-same confronta puntatori intelligenti.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) funzione

Are-same confronta eccezioni.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

gtest-styled assertion result.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) funzione

Are-same confronta valori non puntatore.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di oggetto LHS. |
| T2 | Tipo di oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |

### Valore di ritorno

gtest-styled assertion result.

## Vedi anche

* Struttura [IsSmartPtr](../../system/issmartptr/)
* Struttura [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Spazio dei nomi [System::TestPredicates](../)
* Libreria [Aspose.Slides](../../)