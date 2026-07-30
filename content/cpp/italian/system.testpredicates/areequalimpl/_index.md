---
title: AreEqualImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta per uguaglianza i numeri in virgola mobile con i tipi aritmetici.
type: docs
weight: 27
url: /it/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) funzione


Confronta per uguaglianza i numeri in virgola mobile con i tipi aritmetici.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | Valore LHS. |
| rhs | const T2 | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funzione


Confronta per uguaglianza i valori, uno o entrambi dei quali è [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funzione


Confronta per uguaglianza i tipi non puntatore usando il metodo Equals fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) funzione


Confronta per uguaglianza i tipi non puntatore usando il metodo Equals fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) funzione


Confronta per uguaglianza i tipi non puntatore usando l'operatore == fornito.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) funzione


Confronta per uguaglianza i boxable con valori [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) funzione


Confronta per uguaglianza i boxable con valori [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) funzione


Confronta per uguaglianza il literal di stringa con valori [SmartPtr](../../system/smartptr/) usando l'unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const char16_t * | Valore LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) funzione


Confronta per uguaglianza il literal di stringa con valori [SmartPtr](../../system/smartptr/) usando l'unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valore LHS. |
| rhs | const char16_t * | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) funzione


Confronta per uguaglianza tipo casuale con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| lhs | T | Valore LHS. |
| s | std::nullptr_t | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) funzione


Confronta per uguaglianza tipo casuale con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs_expr | const char * | Espressione LHS. |
| rhs_expr | const char * | Espressione RHS. |
| rhs | std::nullptr_t | Valore RHS. |
| s | T | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funzione


Confronta per uguaglianza i tipi puntatore.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) funzione


Confronta per uguaglianza i tipi puntatore.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) funzione


Confronta per uguaglianza un tipo casuale con un valore [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
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
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) funzione


Confronta per uguaglianza un valore [Nullable](../../system/nullable/) con un tipo casuale.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
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
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Valore LHS. |
| rhs | T2 | Valore RHS. |
| s | long long | Un parametro di servizio che funge da selettore dell'implementazione della funzione; il valore del parametro è ignorato |

### Valore di ritorno

Risultato dell'asserzione in stile gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) funzione


Confronta per uguaglianza tipi casuali usando gli algoritmi gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)