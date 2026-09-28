---
title: AreNotEqualImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Il confronto di disuguaglianza confronta valori, uno o entrambi dei quali è Decimal.
type: docs
weight: 53
url: /it/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Il confronto di disuguaglianza confronta valori, uno o entrambi dei quali è [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'oggetto LHS. |
| T2 | Tipo dell'oggetto RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Il confronto di disuguaglianza confronta due valori [System::String](../../system/string/), proteggendo dall'invocazione di una funzione membro su un [String](../../system/string/) nullo. È templatizzato per gli stessi motivi di esclusione basati sulla deduzione dell'overload [String](../../system/string/) di AreEqualImpl sopra.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/), vincolato a [System::String](../../system/string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T\& | Valore LHS. |
| rhs | const T\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Il confronto di disuguaglianza confronta tipi non puntatore usando il metodo Equals fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T\& | Valore LHS. |
| rhs | const T\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Il confronto di disuguaglianza confronta tipi non puntatore usando il metodo Equals fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T\& | Valore LHS. |
| rhs | const T\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Il confronto di disuguaglianza confronta tipi non puntatore usando l'operatore != fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T\& | Valore LHS. |
| rhs | const T\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Il confronto di disuguaglianza confronta oggetti boxabili con valori [SmartPtr](../../system/smartptr/) usando l'unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T | Valore LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Il confronto di disuguaglianza confronta oggetti boxabili con valori [SmartPtr](../../system/smartptr/) usando l'unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valore LHS. |
| rhs | T | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Il confronto di disuguaglianza confronta un tipo casuale con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T | Valore LHS. |
| s | std::nullptr_t | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Il confronto di disuguaglianza confronta un tipo casuale con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| rhs | std::nullptr_t | Valore RHS. |
| s | T | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Il confronto di uguaglianza confronta tipi puntatore.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const T1\& | Valore LHS. |
| rhs | const T2\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Il confronto di uguaglianza confronta tipi casuali usando gli algoritmi gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T1 | Valore LHS. |
| rhs | T2 | Valore RHS. |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## Vedi anche

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* classe [String](../../system/string/)
* classe [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)