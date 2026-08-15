---
title: type
second_title: Aspose.Slides C++ API 參考
description: 用於保存指定方法參數的 Tuple。
type: docs
weight: 1
url: /zh-hant/system/methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## 類型 typedef

[Tuple](../../tuple/) 用於保存指定方法的參數。

```cpp
using System::MethodArgumentTuple< R(*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 另見

* 結構 [MethodArgumentTuple< R(*)(Args...)>](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)