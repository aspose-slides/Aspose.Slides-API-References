---
title: WeakPtr()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un puntatore nullo.
type: docs
weight: 1
url: /it/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) costruttore


Crea un puntatore nullo.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) costruttore


Crea un puntatore debole all'oggetto fornito.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) per creare un puntatore debole a. |

## WeakPtr::WeakPtr(const SmartPtr_\&) costruttore


Crea un puntatore debole che fa riferimento allo stesso puntatore a cui punta ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Puntatore da cui copiare il valore referenziato. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) costruttore


Crea un puntatore debole che fa riferimento allo stesso puntatore a cui punta x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo di oggetto referenziato del puntatore di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Puntatore da cui copiare il valore referenziato. |

## WeakPtr::WeakPtr(const WeakPtr_\&) costruttore


Copia il costruttore del puntatore debole.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Puntatore da cui copiare il valore referenziato. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) costruttore


Copia il costruttore del puntatore debole.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo di oggetto referenziato di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Puntatore da cui copiare il valore referenziato. |

## WeakPtr::WeakPtr(SmartPtr_\&&) costruttore


Costruisce tramite spostamento un puntatore debole.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Puntatore da cui spostare il valore referenziato. |

## Vedi anche

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Classe [WeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)