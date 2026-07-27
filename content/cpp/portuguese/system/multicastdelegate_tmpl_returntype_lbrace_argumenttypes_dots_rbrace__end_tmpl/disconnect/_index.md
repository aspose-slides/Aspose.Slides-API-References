---
title: disconnect()
second_title: Referência da API Aspose.Slides para C++
description: Remove o delegate especificado da coleção de delegates.
type: docs
weight: 170
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) método


Remove o delegate especificado da coleção de delegates.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | O delegate a ser removido da coleção |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) método


Remove o método não-estático especificado do objeto especificado da coleção de delegates.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| MemberType | O tipo do método não-estático que será removido da coleção de delegates |
| ClassType | O tipo do objeto cujo método será removido da coleção de delegates |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Um ponteiro para o método não-estático do objeto especificado |
| obj | ClassType * | Um ponteiro para o objeto cujo método será removido da coleção de delegates |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) método


Remove o método não-estático especificado do objeto especificado da coleção de delegates.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| MemberType | O tipo do método não-estático que será removido da coleção de delegates |
| ClassType | O tipo do objeto cujo método será removido da coleção de delegates |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Um ponteiro para o método não-estático do objeto especificado |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Um ponteiro compartilhado para o objeto cujo método será removido da coleção de delegates |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) método


Remove o objeto MulticastDelegate especificado da coleção de delegates.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Uma instância da classe MulticastDelegate a ser removida da coleção de delegates |

### Valor de Retorno

Uma referência ao próprio objeto

## Ver também

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Método [MulticastDelegate](../multicastdelegate/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)