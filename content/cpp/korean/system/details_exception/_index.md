---
title: Details_Exception
second_title: Aspose.Slides for C++ API 레퍼런스
description: "예외를 나타냅니다. 이 클래스를 수동으로 인스턴스화하지 마십시오. 대신 Exception 클래스를 사용하십시오. Exception 클래스 인스턴스를 System::SmartPtr으로 감싸지 마십시오."
type: docs
weight: 417
url: /ko/system/details_exception/
---
## Details_Exception 클래스

Represents an exception. Never create instances of this class manually. Use the Exception class instead. Never wrap the Exception class instances into [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | 예외 래퍼에 의해 래핑된 예외 인스턴스를 발생시킵니다. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(또는 NaN)과도 같지 않음에도 불구하고, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(또는 NaN)과도 같지 않음에도 불구하고, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | 사용자 정의 예외 데이터를 포함하는 사전을 반환합니다. |
| **int32_t** [get_HResult](./get_hresult/)() const | 현재 객체가 나타내는 예외와 연관된 HRESULT 코드인 32비트 정수 값을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | 내부 예외를 나타내는 객체에 대한 참조를 반환합니다. |
| virtual [String](../string/) [get_Message](./get_message/)() const | 오류 설명이 포함된 문자열을 반환합니다. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | 스택 트레이스가 포함된 문자열을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | 가장 내부의 예외를 나타내는 Exception 객체의 복사본을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_HResult](./set_hresult/)(**int32_t**) | 특정 예외에 할당된 코드화된 숫자값인 HRESULT를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 템플릿 인수 n번째를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](./tostring/)() const override | 현재 객체의 문자열 표현을 반환합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual const char * [what](./what/)() const | [what()](./what/) 메서드를 구현합니다. 이 메서드는 [ExceptionWrapper](../exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception에서 상속받지 않았음에도 불구하고 파생 클래스는 보호/비공개 멤버를 사용하여 로직을 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../exceptionwrapper/) 로 이동하면 해당 로직이 깨질 수 있습니다. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)