---
title: operator=()
second_title: Riferimento API di Aspose.Slides per C++
description: Assegna per spostamento l'oggetto SmartPtr. x diventa inutilizzabile.
type: docs
weight: 27
url: /it/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) metodo


Assegna per spostamento l'oggetto [SmartPtr](../). x diventa inutilizzabile.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntatore da assegnare per spostamento. |

### Valore restituito

Riferimento a questo oggetto.

## SmartPtr::operator=(const SmartPtr_\&) metodo


Assegna per copia l'oggetto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Puntatore da assegnare per copia. |

### Valore restituito

Riferimento a questo oggetto.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) metodo


Assegna per copia l'oggetto [SmartPtr](../). Esegue le conversioni di tipo richieste.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo dell'oggetto puntato da x. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Puntatore da assegnare per copia. |

### Valore restituito

Riferimento a questo oggetto.

## SmartPtr::operator=(Pointee_ *) metodo


Assegna un puntatore grezzo all'oggetto [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Valore del puntatore da assegnare. |

### Valore restituito

Riferimento a questo oggetto.

## SmartPtr::operator=(std::nullptr_t) metodo


Imposta il valore del puntatore a nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Valore restituito

Riferimento a questo oggetto.

## Vedi anche

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)