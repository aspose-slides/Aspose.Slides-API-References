---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 레퍼런스
description: "함수, 메서드 또는 함수 객체에 대한 포인터를 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 절대로 System::SmartPtr 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오."
type: docs
weight: 287
url: /ko/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> 클래스

함수, 메서드 또는 함수 객체에 대한 포인터를 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ReturnType | 함수, 메서드 또는 함수 객체 포인터의 반환 타입이며, 이 클래스가 나타냅니다. |
| ArgumentTypes | 함수, 메서드 또는 함수 객체 포인터의 인수 목록이며, 이 클래스가 나타냅니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [Delegate](./delegate/)() | 기본 생성자. 아무 것도 가리키지 않는 delegate 객체를 생성합니다. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | 이동 복사 생성자. 지정된 delegate가 가리키는 엔터티의 소유권을 가져옵니다. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | 생성자. 지정된 자유 함수 또는 정적 메서드 포인터로부터 delegate 객체를 생성합니다. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | 생성자. std::bind()에 의해 생성된 함수 객체 포인터로부터 delegate를 생성합니다. |
|  [Delegate](./delegate/)(int, T\&) | 생성자. 지정된 함수 객체로부터 delegate를 생성합니다. |
|  [Delegate](./delegate/)(long, T\&&) | 이동 생성자. 지정된 함수 객체로부터 delegate를 생성합니다. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | 생성자. 지정된 객체의 지정된 비정적 메서드를 가리키는 delegate를 생성합니다. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 생성자. 지정된 객체의 지정된 비정적 메서드를 가리키는 delegate를 생성합니다. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | std::function 함수 객체를 가리키는 delegate 객체를 생성합니다. |
| **bool** [Empty](./empty/)() const | 현재 delegate 객체가 비어 있는지 확인합니다. 예: 어떤 엔터티도 가리키지 않음. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 현재 delegate 객체가 가리키는 함수, 메서드 또는 함수 객체를 호출합니다. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | 이동 할당 연산자. 지정된 delegate가 가리키는 엔터티의 소유권을 가져옵니다. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | 두 delegate 객체를 비교하여 동일한 엔터티를 가리키는지 확인합니다. |

## 비고

```cpp
#include "system/delegate.h"
#include <iostream"

// 위임을 선언합니다.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // 변수에 PrintMessage 함수의 주소를 할당합니다.
  Message mes = Message(&PrintMessage);

  // 함수를 호출합니다.
  mes();

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
안녕, 세계!
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)