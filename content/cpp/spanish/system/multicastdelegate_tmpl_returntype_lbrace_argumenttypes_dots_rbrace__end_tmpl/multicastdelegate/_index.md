---
title: MulticastDelegate()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una colección vacía.
type: docs
weight: 1
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() método

Construye una colección vacía.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) método

Equivalente al constructor predeterminado.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) método

Realiza una copia superficial de la colección de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | const MulticastDelegate\& | Una instancia de la clase MulticastDelegate desde la cual copiar la colección de delegados. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) método

Constructor de movimiento.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | MulticastDelegate\&& | Una instancia de la clase MulticastDelegate desde la cual mover la colección de delegados. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) método

Construye una instancia y coloca el delegado especificado en la colección de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Un delegado para añadir a la colección de delegados |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) método

Construye una instancia y añade el valor especificado a la colección de delegados.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del valor que se añadirá a la colección de delegados de la instancia recién construida; el tipo debe poder convertirse al tipo Callback. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg | T | Un valor para añadir a la colección de delegados |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) método

Construye una instancia y añade el valor especificado a la colección de delegados.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Un valor para añadir a la colección de delegados |

## Ver también

* Typedef [Callback](../callback/)
* Clase [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)