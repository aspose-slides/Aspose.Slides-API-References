---
title: IsList
second_title: Aspose.Slides for C++ API 참조
description: "형식이 System::Collections::Generic::List 특수화인지 확인합니다. 해당되는 경우 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다."
type: docs
weight: 118
url: /ko/system.testpredicates.typetraits/islist/
---
## IsList typedef


형식이 [System::Collections::Generic::List](../../system.collections.generic/list/) 특수화인지 확인합니다. 해당되는 경우 value 멤버가 true로 설정되고, 그렇지 않으면 false로 설정됩니다.

```cpp
using System::TestPredicates::TypeTraits::IsList = typedef std::is_same<T, System::Collections::Generic::List<typename T::ValueType> >
```


## 참조

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)