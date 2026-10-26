---
title: AreEqualData()
second_title: Riferimento API di Aspose.Slides per C++
description: "Confronta per uguaglianza due contenitori usando System::Object::Equals sugli elementi. Funziona per elementi SmartPtr."
type: docs
weight: 14
url: /it/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) funzione

Confronta per uguaglianza due contenitori usando [System::Object::Equals](../../system/object/equals/) sugli elementi. Funziona per [SmartPtr](../../system/smartptr/) elementi.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo del contenitore LHS. |
| T2 | Tipo del contenitore RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | const T1\& | Riferimento al contenitore LHS. |
| rhs | const T2\& | Riferimento al contenitore RHS. |

### Valore di ritorno

True se gli elementi contenuti e le dimensioni corrispondono, false altrimenti.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) funzione

Confronta per uguaglianza due contenitori usando l'operatore == sugli elementi. Funziona per elementi non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo del contenitore LHS. |
| T2 | Tipo del contenitore RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | const T1\& | Contenitore LHS. |
| rhs | const T2\& | Contenitore RHS. |

### Valore di ritorno

True se gli elementi contenuti e le dimensioni corrispondono, false altrimenti.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) funzione

Confronta per uguaglianza due contenitori di tipo identico. Funziona per elementi non-SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo del contenitore LHS. |
| T2 | Tipo del contenitore RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | const T\& | Contenitore LHS. |
| rhs | const T\& | Contenitore RHS. |

### Valore di ritorno

True se gli elementi contenuti e le dimensioni corrispondono, false altrimenti.

## Vedi anche

* Struttura [IsSmartPtr](../../system/issmartptr/)
* Spazio dei nomi [System::TestPredicates::Details::SharedPtrAsserts](../)
* Libreria [Aspose.Slides](../../)