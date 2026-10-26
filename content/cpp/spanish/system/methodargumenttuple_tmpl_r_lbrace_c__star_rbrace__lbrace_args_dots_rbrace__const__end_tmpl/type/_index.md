---
title: type
second_title: Referencia de la API de Aspose.Slides para C++
description: Tupla para almacenar argumentos del método especificado.
type: docs
weight: 1
url: /es/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## tipo typedef


[Tuple](../../tuple/) para almacenar argumentos del método especificado.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## Ver también

* Estructura [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)