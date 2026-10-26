---
title: ValueType
second_title: Aspose.Slides for C++ API 레퍼런스
description: "포인터된 배열의 저장 유형. T가 System::Array의 특수화인 경우에만 의미가 있습니다."
type: docs
weight: 508
url: /ko/system/smartptr/valuetype/
---
## ValueType typedef

포인터된 배열의 저장 유형. T가 [System::Array](../../array/)의 특수화인 경우에만 의미가 있습니다.

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## 참조

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)