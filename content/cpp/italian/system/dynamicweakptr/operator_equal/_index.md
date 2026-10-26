---
title: operator=()
second_title: Riferimento API Aspose.Slides per C++
description: Assegna mediante spostamento il puntatore intelligente.
type: docs
weight: 27
url: /it/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) metodo


Assegna mediante spostamento il puntatore intelligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntatore da cui eseguire l'assegnazione mediante spostamento del valore. |

### Valore di ritorno

Riferimento a se stesso.

## DynamicWeakPtr::operator=(const SmartPtr_&) metodo


Assegna mediante copia il puntatore intelligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Puntatore da cui eseguire l'assegnazione mediante copia del valore. |

### Valore di ritorno

Riferimento a se stesso.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metodo


Assegna mediante copia il puntatore intelligente.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo di oggetto puntato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Puntatore da cui eseguire l'assegnazione mediante copia del valore. |

### Valore di ritorno

Riferimento a se stesso.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metodo


Assegna il puntatore intelligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Valore del puntatore. |

### Valore di ritorno

Riferimento a se stesso.

## DynamicWeakPtr::operator=(std::nullptr_t) metodo


Imposta il puntatore intelligente a null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Valore di ritorno

Riferimento a se stesso.

## Vedi anche

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Classe [DynamicWeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)