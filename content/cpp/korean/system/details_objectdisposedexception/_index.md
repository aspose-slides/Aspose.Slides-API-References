---
title: Details_ObjectDisposedException
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ObjectDisposedException은 해제된 객체에서 메서드를 호출할 때 발생합니다. 이 클래스를 수동으로 인스턴스화하지 마십시오. 대신 ObjectDisposedException 클래스를 사용하십시오. ObjectDisposedException 클래스 인스턴스를 System::SmartPtr에 감싸지 마십시오."
type: docs
weight: 612
url: /ko/system/details_objectdisposedexception/
---
## Details_ObjectDisposedException 클래스


ObjectDisposedException은 해제된 객체에서 메서드를 호출할 때 발생합니다. 이 클래스를 수동으로 인스턴스화하지 마십시오. 대신 ObjectDisposedException 클래스를 사용하십시오. ObjectDisposedException 클래스 인스턴스를 [System::SmartPtr](../smartptr/)에 감싸지 마십시오.

```cpp
class Details_ObjectDisposedException : public System::Details_InvalidOperationException
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-style 부동 소수점 비교를 에뮬레이션하며, IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-style 부동 소수점 비교를 에뮬레이션하며, IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | 사용자 정의 예외 데이터를 포함한 사전을 반환합니다. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 현재 객체가 나타내는 예외와 연결된 32비트 정수 값을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 내부 예외를 나타내는 객체에 대한 참조를 반환합니다. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | 오류 설명을 포함하는 문자열을 반환합니다. |
| [String](../string/) [get_ObjectName](./get_objectname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | 스택 추적을 포함하는 문자열을 반환합니다. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 가장 내부 예외를 나타내는 Exception 객체의 복사본을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드의 analog입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출의 analog입니다. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() 문에 대한 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드의 analog입니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 특정 예외에 할당되는 코드화된 숫자 값인 HRESULT를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 현재 객체의 문자열 표현을 반환합니다. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() 문에 대한 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) 메서드를 구현하며, 이 메서드는 [ExceptionWrapper](../exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception에서 상속되지 않았음에도 파생 클래스는 보호/비공개 멤버를 사용해 로직을 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../exceptionwrapper/)로 옮기면 해당 로직이 깨질 수 있습니다. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Details_InvalidOperationException](../details_invalidoperationexception/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)