---
title: type
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたメソッドの引数を保持するタプル。
type: docs
weight: 1
url: /ja/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## typedef の型


[Tuple](../../tuple/) は指定されたメソッドの引数を保持します。

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 参照

* 構造体 [MethodArgumentTuple< R(C::*)(Args...)>](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)