---
title: MulticastDelegate()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma coleção vazia.
type: docs
weight: 1
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

Constrói uma coleção vazia.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

Equivalente ao construtor padrão.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

Realiza uma cópia superficial da coleção de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| o | const MulticastDelegate\& | Uma instância da classe MulticastDelegate da qual copiar a coleção de delegados. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

Construtor de movimentação.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| o | MulticastDelegate\&& | Uma instância da classe MulticastDelegate da qual mover a coleção de delegados. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

Constrói uma instância e adiciona o delegado especificado à coleção de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Um delegado a ser adicionado à coleção de delegados |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

Constrói uma instância e adiciona o valor especificado à coleção de delegados.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do valor a ser adicionado à coleção de delegados da instância recém-construída; o tipo deve ser convertido para o tipo Callback. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arg | T | Um valor a ser adicionado à coleção de delegados |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

Constrói uma instância e adiciona o valor especificado à coleção de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Um valor a ser adicionado à coleção de delegados |

## Ver Também

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)