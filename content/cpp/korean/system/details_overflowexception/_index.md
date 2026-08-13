---
title: Details_OverflowException
second_title: Aspose.Slides for C++ API 참조
description: "OverflowException은 연산 결과가 오버플로우가 발생할 때 발생합니다. 이 클래스를 수동으로 인스턴스화하지 마십시오. 대신 OverflowException 클래스를 사용하십시오. OverflowException 클래스 인스턴스를 System::SmartPtr에 절대로 래핑하지 마십시오."
type: docs
weight: 651
url: /ko/system/details_overflowexception/
---
## Details_OverflowException 클래스


OverflowException은 연산 결과가 오버플로우가 발생할 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 OverflowException 클래스를 사용하십시오. OverflowException 클래스 인스턴스를 [System::SmartPtr](../smartptr/)에 절대로 래핑하지 마십시오.

```cpp
class Details_OverflowException : public System::Details_ArithmeticException
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C#-style 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C#-style 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | 사용자 정의 예외 데이터를 포함하는 사전을 반환합니다. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 현재 객체가 나타내는 예외와 연결된 HRESULT 코드인 32비트 정수 값을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 내부 예외를 나타내는 객체에 대한 참조를 반환합니다. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | 오류 설명이 포함된 문자열을 반환합니다. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | 스택 트레이스가 포함된 문자열을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 가장 내부 예외를 나타내는 Exception 객체의 복사본을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드의 유사품입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출의 유사품입니다. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드의 유사품입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 특정 예외에 할당된 코드화된 숫자 값인 HRESULT를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 현재 객체의 문자열 표현을 반환합니다. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() 문 구문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) 메서드를 구현하며, 이 메서드는 [ExceptionWrapper](../exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception에서 상속되지 않았음에도 파생 클래스는 protected/private 멤버를 사용하여 논리를 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../exceptionwrapper/)로 이동하면 해당 논리가 깨질 수 있습니다. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [Details_ArithmeticException](../details_arithmeticexception/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)