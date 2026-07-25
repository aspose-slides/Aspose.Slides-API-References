---
title: type
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたメソッドの引数を保持するタプル。
type: docs
weight: 1
url: /ja/system/methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## 型 typedef

[Tuple](../../tuple/) は指定されたメソッドの引数を保持します。

```cpp
using System::MethodArgumentTuple< R(*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 参照

* Struct [MethodArgumentTuple< R(*)(Args...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)