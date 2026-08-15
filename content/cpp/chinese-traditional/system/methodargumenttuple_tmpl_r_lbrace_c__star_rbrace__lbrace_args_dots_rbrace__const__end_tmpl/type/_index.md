---
title: type
second_title: Aspose.Slides for C++ API 參考
description: 用於保存指定方法參數的元組。
type: docs
weight: 1
url: /zh-hant/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/type/
---
## 類型 typedef


[Tuple](../../tuple/) 用於保存指定方法的參數。

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...) const >::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 另見

* 結構 [MethodArgumentTuple< R(C::*)(Args...) const >](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)