---
title: Predicate
second_title: Aspose.Slides for C++ API 참조
description: Predicate에 대한 포인터를 나타냅니다 - 단일 인자를 받아 bool 값을 반환하는 호출 가능한 엔터티입니다.
type: docs
weight: 4187
url: /ko/system/predicate/
---
## Predicate 타입 정의


Predicate에 대한 포인터를 나타냅니다 - 단일 인수를 받아 bool 값을 반환하는 호출 가능한 엔터티.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## 비고



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // 배열을 채웁니다.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // 3보다 큰 배열 요소를 반환하는 프레디케이트를 생성합니다.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // 생성된 프레디케이트를 사용해 배열의 첫 번째 요소를 찾아 출력합니다.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
5
*/
```

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)