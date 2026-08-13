---
title: BothEnumerable
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 타입 인수가 모두 IEnumerable인지 확인합니다. 그렇다면 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다.
type: docs
weight: 144
url: /ko/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable typedef

두 타입 인수가 모두 IEnumerable인지 확인합니다. 그렇다면 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다.

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable = typedef std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```

## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)