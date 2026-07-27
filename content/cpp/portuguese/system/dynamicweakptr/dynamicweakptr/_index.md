---
title: DynamicWeakPtr()
second_title: Referência da API Aspose.Slides para C++
description: Cria um ponteiro inteligente nulo.
type: docs
weight: 1
url: /pt/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) construtor


Cria um ponteiro inteligente nulo.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) construtor


Cria um ponteiro inteligente que aponta para o objeto fornecido.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Apontado. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) construtor


Constrói uma cópia do ponteiro inteligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Ponteiro inteligente para copiar informações do apontado. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) construtor


Constrói uma cópia do ponteiro inteligente.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do apontado do ponteiro de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Ponteiro inteligente para copiar informações do apontado. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) construtor


Constrói uma cópia do ponteiro inteligente.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Ponteiro inteligente para copiar informações do apontado. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) construtor


Constrói um ponteiro inteligente por movimento.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ponteiro inteligente para mover informações do apontado. Torna-se inutilizável após a chamada. |

## Veja também

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Classe [DynamicWeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)