---
title: Action
second_title: Aspose.Slides for C++ API 참조
description: 반환 값이 없는 메서드를 참조하는 대리자 유형입니다.
type: docs
weight: 3602
url: /ko/system/action/
---
## Action 타입 정의

반환 값이 없는 메서드를 참조하는 대리자 유형입니다.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## 비고



```cpp
#include <system/action.h>

using namespace System;

// 전달된 문자열을 출력하는 함수입니다.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action 인스턴스를 생성합니다.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // 액션을 호출합니다.
  action(u"Hello, world!");

  return 0;
}
/*
이 코드 예제는 다음 출력 결과를 생성합니다:
Hello, world!
*/
```

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)