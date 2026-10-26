---
title: DefaultBoxedValue
second_title: Aspose.Slides for C++ API 레퍼런스
description: "BoxedValue 클래스 구현. 공통 코드를 중복하지 않고 BoxingValue 특수화를 선언할 수 있게 합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생하므로 절대 생성하지 마십시오. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 274
url: /ko/system/defaultboxedvalue/
---
## DefaultBoxedValue 클래스


[BoxedValue](../boxedvalue/) 클래스 구현. 공통 코드를 중복하지 않고 BoxingValue 특수화를 선언할 수 있도록 합니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 만들거나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생하므로 절대 생성하지 마십시오. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고, 해당 포인터를 인자로 함수에 전달하십시오.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | 지정된 값을 나타내는 [DefaultBoxedValue](./) 클래스의 새 인스턴스를 생성합니다. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 현재 및 지정된 객체가 나타내는 박싱된 값들의 동등성을 결정합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 동등하지 않지만, 여기서는 두 NaN을 동등하게 취급합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 동등하지 않지만, 여기서는 두 NaN을 동등하게 취급합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 전용입니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const override | 현재 객체에 대한 해시 코드를 반환합니다. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 객체의 실제 유형을 가져옵니다. |
| **bool** [is](./is/)() const | 현재 객체가 나타내는 박싱된 값의 유형이 **V**인지 확인합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 동작입니다. |
| void [Lock](../object/lock/)() | C# lock() 문을 구현한 잠금 기능입니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 허용합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 허용합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 허용합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](./tostring/)() const override | 박싱된 값의 문자열 표현을 반환합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| const T\& [unbox](./unbox/)() const | 박싱된 값을 언박싱합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 문 해제 기능을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)