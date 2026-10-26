---
title: AreEqualContainer()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due contenitori usando l'operatore == sugli elementi. Funziona per elementi non-SmartPtr.
type: docs
weight: 1
url: /it/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funzione


Confronta due contenitori usando l'operatore == sugli elementi. Funziona per elementi non-SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo del contenitore LHS. |
| T2 | Tipo del contenitore RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Contenitore LHS. |
| rhs | const T2\& | Contenitore RHS. |

### Valore di ritorno

Vero se gli elementi contenuti e le dimensioni corrispondono, false altrimenti.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funzione


Confronta due contenitori usando [System::Object::Equals](../../system/object/equals/) sugli elementi. Funziona per elementi [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo del contenitore LHS. |
| T2 | Tipo del contenitore RHS. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Riferimento al contenitore LHS. |
| rhs | const T2\& | Riferimento al contenitore RHS. |

### Valore di ritorno

Vero se gli elementi contenuti e le dimensioni corrispondono, false altrimenti.

## Vedi anche

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)