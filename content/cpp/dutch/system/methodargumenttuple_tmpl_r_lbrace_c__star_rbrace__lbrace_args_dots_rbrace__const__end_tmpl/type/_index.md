---
title: type
second_title: Aspose.Slides voor C++ API-referentie
description: Tuple om argumenten van de opgegeven methode vast te houden.
type: docs
weight: 1
url: /nl/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## type typedef


[Tuple](../../tuple/) om argumenten van de opgegeven methode vast te houden.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## Zie ook

* Struct [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)