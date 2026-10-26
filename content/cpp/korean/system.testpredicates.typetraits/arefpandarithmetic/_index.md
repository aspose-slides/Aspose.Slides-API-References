---
title: AreFPandArithmetic
second_title: C++용 Aspose.Slides API 참조
description: T1이 산술형이고 T2가 부동소수점형이거나 그 반대인지 확인합니다. 그렇다면 value 멤버를 true로 설정하고, 그렇지 않으면 false입니다.
type: docs
weight: 79
url: /ko/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic 타입 정의

**T1**이 산술형이고 **T2**가 부동소수점형이거나 그 반대인지를 확인합니다. 그렇다면 value 멤버를 true로 설정하고, 그렇지 않으면 false입니다.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)