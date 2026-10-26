---
title: type
second_title: Aspose.Slides für C++ API-Referenz
description: Tupel zum Halten von Argumenten der angegebenen Methode.
type: docs
weight: 1
url: /de/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## Typ typedef


[Tuple](../../tuple/) zum Halten von Argumenten der angegebenen Methode.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## Siehe auch

* Struktur [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)