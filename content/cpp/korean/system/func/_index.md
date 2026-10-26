---
title: Func
second_title: Aspose.Slides for C++ API 참조
description: "함수 대리자. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 859
url: /ko/system/func/
---
## Func 클래스

함수 대리자. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 호출 인수, 그 뒤에 필수 반환 타입. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [Func](./func/)() | null-Func를 생성하는 기본 생성자. |
|  [Func](./func/)(T\&&) | [Func](./) 객체를 생성하고 값(실제 콜백 또는 nullptr)을 할당하는 생성자. |
|  [Func](./func/)(const [Func](./)\&) | 복사 생성자. |
|  [Func](./func/)([Func](./)\&&) | 이동 생성자. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | 복사 할당. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | 이동 할당. |
|  [~Func](./~func/)() | 소멸자. |

## 비고

```cpp
#include "system/func.h"
#include <iostream"

// 이 함수는 System::Func 대리자 인스턴스를 매개변수로 받아들입니다.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // System::Func 대리자 인스턴스를 생성합니다.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // 만든 인스턴스를 함수 인수로 전달합니다.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
1
4
9
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)