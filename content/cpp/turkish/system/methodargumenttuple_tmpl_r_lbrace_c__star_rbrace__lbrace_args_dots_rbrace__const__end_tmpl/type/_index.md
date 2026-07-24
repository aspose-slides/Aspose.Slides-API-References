---
title: type
second_title: Aspose.Slides için C++ API Referansı
description: Belirli bir yöntemin argümanlarını tutan Tuple.
type: docs
weight: 1
url: /tr/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## tip typedef


[Tuple](../../tuple/) belirli bir yöntemin argümanlarını tutmak için.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## Bakınız

* Struct [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)