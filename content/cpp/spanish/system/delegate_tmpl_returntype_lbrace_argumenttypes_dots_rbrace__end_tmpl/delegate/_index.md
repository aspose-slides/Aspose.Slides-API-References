---
title: Delegate()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor predeterminado. Construye el objeto delegado que no apunta a nada.
type: docs
weight: 1
url: /es/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() método


Constructor predeterminado. Construye el objeto delegado que no apunta a nada.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) método




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) método


Constructor de copia en movimiento. Toma la propiedad de una entidad a la que apunta el delegado especificado.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | Delegate\&& | El objeto Delegate del cual mover la entidad apuntada |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) método


Constructor. Construye un objeto delegado a partir del puntero especificado a una función libre o método estático.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | El tipo del puntero a función o método estático aceptado por el constructor como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| function | T | Puntero a una función o a un método estático al que apuntará la instancia recién creada de Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) método


Constructor. Construye un delegado a partir del puntero especificado al objeto función generado por std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | El tipo del objeto función generado por std::bind() aceptado por el constructor como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| function | T | Puntero a una “expresión bind” – un puntero a función generado por std::bind() – que será apuntado por la instancia recién creada de Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) método


Constructor. Construye un delegado a partir del objeto función especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función aceptado por el constructor como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functor_tag | int | Un valor entero ficticio; este argumento se utiliza para resolver ambigüedades |
| functor | T\& | Un objeto función al que apuntará el delegado recién construido |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) método


Constructor de movimiento. Construye un delegado a partir del objeto función especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función aceptado por el constructor como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functor_tag | long | Un valor entero ficticio; este argumento se utiliza para resolver ambigüedades |
| functor | T\&& | Un objeto función al que apuntará el delegado recién construido |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) método


Constructor. Construye un delegado que apunta al método no estático especificado del objeto especificado.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que el constructor acepta como argumento |
| ClassType | El tipo del objeto que el constructor acepta como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntero al método no estático al que apuntará el delegado recién creado |
| obj | ClassType * | Un puntero a un objeto cuyo método de miembro será apuntado por el delegado recién creado |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) método


Constructor. Construye un delegado que apunta al método no estático especificado del objeto especificado.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que el constructor acepta como argumento |
| ClassType | El tipo del objeto que el constructor acepta como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| member | MemberType MemberClass::* | Un puntero al método no estático al que apuntará el delegado recién creado |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntero compartido a un objeto cuyo método de miembro será apuntado por el delegado recién creado |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) método


Construye un objeto delegado que apunta a un objeto función std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| R | El tipo de retorno del objeto función aceptado por el constructor como argumento |
| Args | La lista de argumentos del objeto función aceptado por el constructor como argumento |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Un objeto función que será apuntado por el objeto delegado recién creado |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)