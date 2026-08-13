---
title: AnyOfDecimal
second_title: Aspose.Slides for C++ API 레퍼런스
description: "형식 인수 중 최소 하나가 System::Decimal인지 확인합니다. 그렇다면 value 멤버를 true로 설정하고, 그렇지 않으면 false입니다."
type: docs
weight: 92
url: /ko/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

형식 인수 중 최소 하나가 [System::Decimal](../../system/decimal/)인지 확인합니다. 그렇다면 value 멤버를 true로 설정하고, 그렇지 않으면 false입니다.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)