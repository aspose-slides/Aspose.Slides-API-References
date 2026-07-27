---
title: connect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega el delegado especificado a la colección.
type: docs
weight: 144
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) método


Agrega el delegado especificado a la colección.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | El delegado a agregar a la colección |

### Valor devuelto

Una referencia a sí mismo

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) método


Agrega el objeto de función especificado a la colección de delegados. El objeto de función se convierte al tipo de delegado Callback antes de ser agregado a la colección.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| R | El tipo de retorno del objeto de función a agregar a la colección |
| Args | La lista de argumentos del objeto de función a agregar a la colección |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | El objeto de función a agregar a la colección |

### Valor devuelto

Una referencia a sí mismo

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) método


Agrega el objeto MulticastDelegate especificado a la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Una instancia de la clase MulticastDelegate a agregar a la colección de delegados |

### Valor devuelto

Una referencia a sí mismo

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) método


Agrega el método no estático especificado del objeto especificado a la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| MemberType | El tipo del método no estático que se agregará a la colección de delegados |
| ClassType | El tipo del objeto cuyo método se agregará al delegado |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | ClassType * | Un puntero a un método miembro del objeto que se agregará a la colección de delegados |

### Valor devuelto

Una referencia a sí mismo

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) método


Agrega el método no estático especificado del objeto especificado a la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| MemberType | El tipo del método no estático que se agregará a la colección de delegados |
| ClassType | El tipo del objeto cuyo método se agregará a la colección de delegados |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntero compartido a un método miembro del objeto que se agregará a la colección de delegados |

### Valor devuelto

Una referencia a sí mismo

## Ver también

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)