---
title: operator()()
second_title: Referencia de API de Aspose.Slides para C++
description: Invoca todos los delegados que están actualmente presentes en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron añadidos a la colección. El operador se bloquea mientras se ejecutan los delegados.
type: docs
weight: 235
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const método

Invoca todos los delegados que están actualmente presentes en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron añadidos a la colección. El operador se bloquea mientras se ejecutan los delegados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | ArgumentTypes... | Argumentos a pasar a los delegados a invocar |

### Valor de retorno

Valor devuelto por el último delegado invocado

## Ver también

* Clase [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)