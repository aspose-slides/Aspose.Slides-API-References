---
title: type
second_title: Aspose.Slides for C++ API 참조
description: 지정된 메서드의 인수를 보관하기 위한 튜플.
type: docs
weight: 1
url: /ko/system/methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/type/
---
## 타입 정의


[Tuple](../../tuple/)는 지정된 메서드의 인수를 보관하기 위해 사용됩니다.

```cpp
using System::MethodArgumentTuple< R(*)(Args...)>::type =  std::tuple<typename std::remove_const<typename std::remove_reference<Args>::type>::type...>
```

## 관련 항목

* 구조체 [MethodArgumentTuple< R(*)(Args...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)