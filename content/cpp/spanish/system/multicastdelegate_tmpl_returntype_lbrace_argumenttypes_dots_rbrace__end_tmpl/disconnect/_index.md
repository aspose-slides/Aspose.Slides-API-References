---
title: disconnect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el delegado especificado de la colección de delegados.
type: docs
weight: 170
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) método


Elimina el delegado especificado de la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [Callback](../callback/) | El delegado que se eliminará de la colección |

### Valor devuelto

Una referencia al propio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) método


Elimina el método no estático especificado del objeto especificado de la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se eliminará de la colección de delegados |
| ClassType | El tipo del objeto cuyo método se eliminará de la colección de delegados |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | ClassType * | Un puntero al objeto cuyo método se eliminará de la colección de delegados |

### Valor devuelto

Una referencia al propio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) método


Elimina el método no estático especificado del objeto especificado de la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se eliminará de la colección de delegados |
| ClassType | El tipo del objeto cuyo método se eliminará de la colección de delegados |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntero compartido a un objeto cuyo método se eliminará de la colección de delegados |

### Valor devuelto

Una referencia al propio objeto

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) método


Elimina el objeto MulticastDelegate especificado de la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Una instancia de la clase MulticastDelegate que se eliminará de la colección de delegados |

### Valor devuelto

Una referencia al propio objeto

## Ver también

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)