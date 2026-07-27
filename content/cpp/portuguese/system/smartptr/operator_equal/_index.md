---
title: operator=()
second_title: Referência da API Aspose.Slides para C++
description: Move-atribuí objeto SmartPtr. x torna-se inutilizável.
type: docs
weight: 27
url: /pt/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) método


Move-assigns [SmartPtr](../) objeto. x torna-se inutilizável.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ponteiro a ser atribuído por movimento. |

### Valor de Retorno

Referência a este objeto.

## SmartPtr::operator=(const SmartPtr_&) método


Copy-assigns [SmartPtr](../) objeto.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Ponteiro a ser atribuído por cópia. |

### Valor de Retorno

Referência a este objeto.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) método


Copy-assigns [SmartPtr](../) objeto. Faz as conversões de tipo necessárias.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do objeto apontado por x. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Ponteiro a ser atribuído por cópia. |

### Valor de Retorno

Referência a este objeto.

## SmartPtr::operator=(Pointee_ *) método


Assigns raw pointer to [SmartPtr](../) objeto.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Valor do ponteiro a ser atribuído. |

### Valor de Retorno

Referência a este objeto.

## SmartPtr::operator=(std::nullptr_t) método


Sets pointer value to nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Valor de Retorno

Referência a este objeto.

## Veja Também

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)