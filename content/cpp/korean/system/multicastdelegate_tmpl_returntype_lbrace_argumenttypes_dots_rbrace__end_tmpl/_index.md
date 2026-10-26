---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 참조
description: "delegate 컬렉션을 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 절대 사용하지 마세요."
type: docs
weight: 1093
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> 클래스

Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) 클래스 to manage objects of this type.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ReturnType | 컬렉션에 있는 각 delegate가 가리키는 호출 가능한 엔터티의 반환 유형 |
| ArgumentTypes | 컬렉션에 있는 각 delegate가 가리키는 호출 가능한 엔터티의 인자 목록 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | 구현되지 않음. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | 지정된 delegate를 컬렉션에 추가합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | 지정된 함수 객체를 delegate 컬렉션에 추가합니다. 함수 객체는 Callback delegate 유형으로 변환된 뒤 컬렉션에 추가됩니다. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | 지정된 MulticastDelegate 객체를 delegate 컬렉션에 추가합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | 지정된 객체의 비정적 메서드를 delegate 컬렉션에 추가합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 지정된 객체의 비정적 메서드를 delegate 컬렉션에 추가합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | 지정된 delegate를 delegate 컬렉션에서 제거합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | 지정된 객체의 비정적 메서드를 delegate 컬렉션에서 제거합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 지정된 객체의 비정적 메서드를 delegate 컬렉션에서 제거합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | 지정된 MulticastDelegate 객체를 delegate 컬렉션에서 제거합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | delegate 컬렉션의 모든 delegate를 제거합니다. |
| **bool** [empty](./empty/)() const | delegate 컬렉션이 비어 있는지 여부를 확인합니다. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | 구현되지 않음. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | 현재 컬렉션에 존재하는 모든 delegate를 호출합니다. delegate는 컬렉션에 추가된 순서대로 호출됩니다. 메서드는 delegate가 실행되는 동안 차단됩니다. |
| **bool** [IsNull](./isnull/)() const | delegate 컬렉션이 비어 있는지 여부를 확인합니다. |
|  [MulticastDelegate](./multicastdelegate/)() | 빈 컬렉션을 생성합니다. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | 기본 생성자와 동일합니다. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | delegate 컬렉션을 얕게 복사합니다. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | 이동 생성자. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | 인스턴스를 생성하고 지정된 delegate를 delegate 컬렉션에 넣습니다. |
|  [MulticastDelegate](./multicastdelegate/)(T) | 인스턴스를 생성하고 지정된 값을 delegate 컬렉션에 넣습니다. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | 인스턴스를 생성하고 지정된 값을 delegate 컬렉션에 넣습니다. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | delegate 컬렉션이 비어 있지 않은지 여부를 확인합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 현재 객체와 지정된 객체인 두 MulticastDelegate 인스턴스가 같지 않은지 여부를 확인합니다. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 현재 컬렉션에 존재하는 모든 delegate를 호출합니다. delegate는 컬렉션에 추가된 순서대로 호출됩니다. 연산자는 delegate가 실행되는 동안 차단됩니다. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | 지정된 delegate를 컬렉션에 추가합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | 지정된 delegate를 delegate 컬렉션에서 제거합니다. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | 지정된 객체가 나타내는 delegate 컬렉션을 현재 객체에 할당합니다. 결과적으로 두 객체는 동일한 delegate 컬렉션을 가리키게 됩니다. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | 이동 할당 연산자. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | delegate 컬렉션이 비어 있는지 여부를 확인합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 현재 객체와 지정된 객체인 두 MulticastDelegate 인스턴스가 같은지 여부를 확인합니다. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | 비어 있는 콜백(실제로 아무것도 호출하지 않음)을 정리합니다. |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | MulticastDelegate 클래스 유형 정보를 나타내는 [TypeInfo](../typeinfo/) 객체에 대한 참조를 반환합니다. |
|  [~MulticastDelegate](./~multicastdelegate/)() | 소멸자. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [Callback](./callback/) | MulticastDelegate 클래스가 나타내는 delegate의 유형입니다. |
| [Function](./function/) | delegate 시그니처와 관련된 함수의 유형입니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)