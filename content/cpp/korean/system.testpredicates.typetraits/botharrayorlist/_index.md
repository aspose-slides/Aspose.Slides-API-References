---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 타입 인수가 모두 배열 또는 리스트인지 확인합니다. 이 경우 value 멤버는 true로 설정되고, 그렇지 않으면 false로 설정됩니다.
type: docs
weight: 131
url: /ko/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

두 타입 인수가 모두 배열 또는 리스트인지 확인합니다. 이 경우 value 멤버는 true로 설정되고, 그렇지 않으면 false로 설정됩니다.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)