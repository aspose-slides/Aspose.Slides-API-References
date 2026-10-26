---
title: type
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 메서드의 인수를 보관하는 튜플.
type: docs
weight: 1
url: /ko/system/methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## 타입 typedef


[Tuple](../../tuple/) 지정된 메서드의 인수를 보관하기 위해.

```cpp
using System::MethodArgumentTuple< R(C::*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 참조

* 구조체 [MethodArgumentTuple< R(C::*)(Args...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)