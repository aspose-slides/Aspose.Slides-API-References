---
title: WeakPtr()
second_title: Referência da API Aspose.Slides para C++
description: Cria ponteiro nulo.
type: docs
weight: 1
url: /pt/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) construtor


Cria ponteiro nulo.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) construtor


Cria ponteiro fraco para o objeto fornecido.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) para criar ponteiro fraco para. |

## WeakPtr::WeakPtr(const SmartPtr_\&) construtor


Cria ponteiro fraco referenciando o mesmo ponteiro que ptr aponta.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Ponteiro para copiar o valor apontado de. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) construtor


Cria ponteiro fraco referenciando o mesmo ponteiro que x aponta.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do objeto apontado do ponteiro fonte. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Ponteiro para copiar o valor apontado de. |

## WeakPtr::WeakPtr(const WeakPtr_\&) construtor


Constrói cópia do ponteiro fraco.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Ponteiro para copiar o valor apontado de. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) construtor


Constrói cópia do ponteiro fraco.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do objeto apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Ponteiro para copiar o valor apontado de. |

## WeakPtr::WeakPtr(SmartPtr_\&&) construtor


Constrói ponteiro fraco movendo.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Ponteiro para mover o valor apontado de. |

## Ver Também

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)