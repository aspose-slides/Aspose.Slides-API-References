---
title: operator=()
second_title: Referência da API Aspose.Slides para C++
description: Move-atribui ponteiro inteligente.
type: docs
weight: 27
url: /pt/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) método


Move-atribui ponteiro inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ponteiro de onde mover-atribuir o valor. |

### Valor de retorno

Referência a si mesmo.

## DynamicWeakPtr::operator=(const SmartPtr_\&) método


Copia-atribui ponteiro inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Ponteiro de onde copiar-atribuir o valor. |

### Valor de retorno

Referência a si mesmo.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) método


Copia-atribui ponteiro inteligente.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Parâmetros de template

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do objeto apontado de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Ponteiro de onde copiar-atribuir o valor. |

### Valor de retorno

Referência a si mesmo.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) método


Atribui ponteiro inteligente.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Valor do ponteiro. |

### Valor de retorno

Referência a si mesmo.

## DynamicWeakPtr::operator=(std::nullptr_t) método


Define ponteiro inteligente como nulo.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Valor de retorno

Referência a si mesmo.

## Ver também

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)