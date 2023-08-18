---
title: type
second_title: Aspose.Slides for C++ API Reference
description: Tuple to hold arguments of specified method.
type: docs
weight: 1
url: /system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## type typedef


[Tuple](../../tuple/) to hold arguments of specified method.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## See Also

* Struct [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)