---
title: DynamicWeakPtr()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un puntatore intelligente nullo.
type: docs
weight: 1
url: /it/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) costruttore

Crea un puntatore intelligente nullo.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) costruttore

Crea un puntatore intelligente che punta all'oggetto fornito.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Oggetto puntato. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) costruttore

Copia il puntatore intelligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Puntatore intelligente da cui copiare le informazioni del puntatore. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) costruttore

Copia il puntatore intelligente.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo di puntatore sorgente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Puntatore intelligente da cui copiare le informazioni del puntatore. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) costruttore

Copia il puntatore intelligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Puntatore intelligente da cui copiare le informazioni del puntatore. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) costruttore

Costruisce spostando il puntatore intelligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntatore intelligente da cui spostare le informazioni del puntatore. Diventa inutilizzabile dopo la chiamata. |

## Vedi anche

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Classe [DynamicWeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)