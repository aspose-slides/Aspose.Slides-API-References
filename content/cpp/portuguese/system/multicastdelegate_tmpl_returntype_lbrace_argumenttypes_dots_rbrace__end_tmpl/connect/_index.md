---
title: connect()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o delegate especificado à coleção.
type: docs
weight: 144
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method

Adiciona o delegate especificado à coleção.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [Callback](../callback/) | O delegate a ser adicionado à coleção |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method

Adiciona o objeto de função especificado à coleção de delegate. O objeto de função é convertido para o tipo delegate Callback antes de ser adicionado à coleção.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| R | O tipo de retorno do objeto de função a ser adicionado à coleção |
| Args | A lista de argumentos do objeto de função a ser adicionado à coleção |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| f | std::function\<R(Args...)> | O objeto de função a ser adicionado à coleção |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method

Adiciona o objeto MulticastDelegate especificado à coleção de delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Uma instância da classe MulticastDelegate a ser adicionada à coleção de delegate |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method

Adiciona o método não estático especificado do objeto especificado à coleção de delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| MemberType | O tipo do método não estático que será adicionado à coleção de delegate |
| ClassType | O tipo do objeto cujo método será adicionado ao delegate |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| member | MemberType ClassType::* | Um ponteiro para o método não estático do objeto especificado |
| obj | ClassType * | Um ponteiro para um objeto cujo método será adicionado à coleção de delegate |

### Valor de Retorno

Uma referência ao próprio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method

Adiciona o método não estático especificado do objeto especificado à coleção de delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| MemberType | O tipo do método não estático que será adicionado à coleção de delegate |
| ClassType | O tipo do objeto cujo método será adicionado à coleção de delegate |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| member | MemberType ClassType::* | Um ponteiro para o método não estático do objeto especificado |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Um ponteiro compartilhado para um objeto cujo método será adicionado à coleção de delegate |

### Valor de Retorno

Uma referência ao próprio objeto

## Ver também

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)