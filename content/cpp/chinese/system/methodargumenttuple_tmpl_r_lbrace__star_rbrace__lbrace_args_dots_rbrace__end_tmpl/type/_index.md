---
title: type
second_title: Aspose.Slides for C++ API 参考
description: 用于保存指定方法的元组。
type: docs
weight: 1
url: /zh/system/methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## 类型 typedef


[Tuple](../../tuple/) 用于保存指定方法的参数。

```cpp
using System::MethodArgumentTuple< R(*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 另请参见

* 结构体 [MethodArgumentTuple< R(*)(Args...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)