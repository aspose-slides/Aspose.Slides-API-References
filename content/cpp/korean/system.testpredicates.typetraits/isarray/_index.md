---
title: IsArray
second_title: Aspose.Slides for C++ API 레퍼런스
description: "type이 System::Array 특수화인지 확인합니다. 그렇다면 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다."
type: docs
weight: 105
url: /ko/system.testpredicates.typetraits/isarray/
---
## IsArray typedef

type이 [System::Array](../../system/array/) 특수화인지 확인합니다. 그렇다면 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다.

```cpp
using System::TestPredicates::TypeTraits::IsArray = typedef std::is_same<T, System::Array<typename T::ValueType> >
```

## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)