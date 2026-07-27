---
title: Delegate()
second_title: Referência da API do Aspose.Slides para C++
description: Construtor padrão. Constrói o objeto delegate que não aponta para nada.
type: docs
weight: 1
url: /pt/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() método


Construtor padrão. Constrói o objeto delegate que não aponta para nada.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) método




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) método


Construtor de cópia de movimentação. Assume a propriedade de uma entidade apontada pelo delegate especificado.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| o | Delegate\&& | O objeto Delegate do qual mover a entidade apontada |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) método


Construtor. Constrói um objeto delegate a partir do ponteiro especificado para uma função livre ou método estático.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| The | tipo do ponteiro para função ou método estático aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| function | T | Ponteiro para uma função ou método estático que será apontado pela instância Delegate recém-criada |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) método


Construtor. Constrói um delegate a partir do ponteiro especificado para o objeto de função gerado por std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| The | tipo do objeto de função gerado por std::bind() aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| function | T | Ponteiro para uma “expressão bind” – um ponteiro de função gerado por std::bind() – que será apontado pela instância Delegate recém-criada |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) método


Construtor. Constrói um delegate a partir do objeto de função especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto de função aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functor_tag | int | Um valor inteiro fictício; este argumento é usado para resolver ambiguidade |
| functor | T\& | Um objeto de função ao qual o delegate recém-construído apontará |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) método


Construtor de movimentação. Constrói um delegate a partir do objeto de função especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto de função aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functor_tag | long | Um valor inteiro fictício; este argumento é usado para resolver ambiguidade |
| functor | T\&& | Um objeto de função ao qual o delegate recém-construído apontará |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) método


Construtor. Constrói um delegate que aponta para o método não estático especificado do objeto especificado.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| MemberType | Tipo do método não estático que o construtor aceita como argumento |
| ClassType | Tipo do objeto aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| member | MemberType ClassType::* | Um ponteiro para o método não estático ao qual o delegate recém-criado apontará |
| obj | ClassType * | Um ponteiro para um objeto cujo método membro será apontado pelo delegate recém-criado |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) método


Construtor. Constrói um delegate que aponta para o método não estático especificado do objeto especificado.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| MemberType | Tipo do método não estático que o construtor aceita como argumento |
| ClassType | Tipo do objeto aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| member | MemberType MemberClass::* | Um ponteiro para o método não estático ao qual o delegate recém-criado apontará |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Um ponteiro compartilhado para um objeto cujo método membro será apontado pelo delegate recém-criado |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) método


Constrói um objeto delegate que aponta para um objeto função std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| R | Tipo de retorno do objeto de função aceito pelo construtor como argumento |
| Args | Lista de argumentos do objeto de função aceito pelo construtor como argumento |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Um objeto de função que será apontado pelo novo objeto delegate criado |

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)