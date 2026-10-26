---
title: TupleFactory
second_title: Aspose.Slides for C++ API 참조
description: 튜플 객체를 생성하기 위한 정적 메서드를 제공합니다.
type: docs
weight: 1366
url: /ko/system/tuplefactory/
---
## TupleFactory 클래스

정적 메서드를 제공하여 튜플 객체를 생성합니다.

```cpp
class TupleFactory
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | 새로운 튜플 객체를 생성합니다. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | 새로운 8-튜플을 생성합니다. 8번째 요소는 [Tuple](../tuple/) 안에 저장됩니다. |
## 비고



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
항목 1: 256
항목 2: 16
항목 3: 64
*/
```

## 참고

* Namespace [System](../)
* Library [Aspose.Slides](../../)