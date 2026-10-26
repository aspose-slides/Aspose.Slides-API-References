---
title: invoke()
second_title: Referencia de API de Aspose.Slides para C++
description: Invoca a todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El método se bloquea mientras se ejecutan los delegados.
type: docs
weight: 222
url: /es/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const método

Invoca a todos los delegados presentes actualmente en la colección de delegados. Los delegados se invocan en el mismo orden en que fueron agregados a la colección. El método se bloquea mientras se ejecutan los delegados.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | ArgumentTypes... | Argumentos que se pasarán a los delegados a invocar |

### Valor de retorno

Valor devuelto del último delegado invocado

## Ver también

* Clase [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)