---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: 저장된 객체의 템플릿 인수들의 포인터 모드를 추적하고 각 할당 후에 업데이트하는 스마트 포인터 클래스입니다. 이 유형은 다른 객체의 삭제를 관리하는 포인터입니다. 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다.
type: docs
weight: 781
url: /ko/system/dynamicweakptr/
---
## DynamicWeakPtr 클래스

스마트 포인터가 저장된 객체의 템플릿 인수들의 포인터 모드를 추적하고 각 할당 후에 업데이트합니다. 이 유형은 다른 객체의 삭제를 관리하는 포인터입니다. 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Pointee | 형식. |
| trunkMode | 스마트 포인터 자체의 모드, shared 또는 weak. |
| weakLeafs | 저장된 타입의 템플릿 인수 인덱스로, weak pointer mode 로 설정되어야 합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| auto [begin](../smartptr/begin/)() | [begin()](../smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [begin](../smartptr/begin/)() const | [begin()](../smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 포인터를 자체 타입으로 캐스팅합니다. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | static_cast를 사용해 포인터를 기본 타입으로 캐스팅합니다. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 캐스팅합니다. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 캐스팅합니다. |
| auto [cbegin](../smartptr/cbegin/)() const | [cbegin()](../smartptr/cbegin/) 메서드에 대한 접근자. SmartPtr_이 [cbegin()](../smartptr/cbegin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [cend](../smartptr/cend/)() const | [cend()](../smartptr/cend/) 메서드에 대한 접근자. SmartPtr_이 [cend()](../smartptr/cend/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 포인터가 가리키는 객체에 const_cast를 사용해 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 포인터가 가리키는 객체에 dynamic_cast를 사용해 다른 타입으로 캐스팅합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | null 스마트 포인터를 생성합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | 주어진 객체를 가리키는 스마트 포인터를 생성합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | 스마트 포인터를 복사 생성합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 스마트 포인터를 복사 생성합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | 스마트 포인터를 복사 생성합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | 스마트 포인터를 이동 생성합니다. |
| auto [end](../smartptr/end/)() | [end()](../smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [end](../smartptr/end/)() const | [end()](../smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 가리키는 객체를 반환합니다. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 포인터 모드를 반환합니다. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 공유 모드에 있는 경우에만 가리키는 객체를 반환하고, 그렇지 않으면 단언합니다. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 참조된 객체에 존재하는 공유 포인터 수(현재 포인터 포함)를 반환합니다. 현재 포인터가 공유 모드임을 단언합니다. |
| int [GetHashCode](../smartptr/gethashcode/)() const | 가리키는 객체에서 [GetHashCode()](../smartptr/gethashcode/)를 호출합니다. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 현재 참조되는 객체를 반환합니다(없으면 예외 발생). |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 가리키는 객체를 반환합니다(없으면 nullptr). [get()](../smartptr/get/)와 동일합니다. |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 참조된 객체를 반환합니다. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 가리키는 객체를 반환합니다(없으면 nullptr). [get()](../smartptr/get/)와 동일합니다. |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 가리키는 객체가 특정 타입이거나 그 하위 타입인지 확인합니다. C#의 'is' 연산자와 동일한 의미를 가집니다. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 포인터가 소유된 객체가 아닌 다른 객체를 가리키는지 확인합니다(앨리어싱 생성자로 생성된 경우). |
| **bool** [IsShared](../smartptr/isshared/)() const | 포인터가 공유 모드인지 확인합니다. |
| **bool** [IsWeak](../smartptr/isweak/)() const | 포인터가 약한(weak) 모드인지 확인합니다. |
| explicit [operator bool](../smartptr/operator_bool/)() const | 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!](../smartptr/operator_not/)() const | 포인터가 null인지 확인합니다. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 가리키는 객체에 대한 참조를 반환합니다. 포인터가 null이 아니어야 함을 단언합니다. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 참조된 객체의 멤버에 접근할 수 있게 합니다. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | 스마트 포인터를 이동 할당합니다. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | 스마트 포인터를 복사 할당합니다. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 스마트 포인터를 복사 할당합니다. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | 스마트 포인터를 지정합니다. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | 스마트 포인터를 null로 설정합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 스마트 포인터가 null인지 확인합니다. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 앨리어싱(앨리어싱 생성자로 만든)을 포인터에서 제거하고, 포인터가 가리키는 동일 객체를 (공유라면 관리, 약하면 추적)하도록 합니다. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 가리키는 객체를 설정합니다. |
| void [reset](../smartptr/reset/)() | 포인터가 nullptr를 가리키게 합니다. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 포인터 모드를 설정합니다. 참조된 객체의 레퍼런스 카운트를 변경할 수 있습니다. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 가리키는 객체(있는 경우)에서 SetTemplateWeakPtr() 메서드를 호출합니다. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 필요한 모드의 [SmartPtr](../smartptr/) 객체를 생성합니다. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 필요한 모드의 null 포인터 [SmartPtr](../smartptr/) 객체를 생성합니다. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 지정된 객체를 가리키는 [SmartPtr](../smartptr/)를 생성하거나, 원시 포인터를 [SmartPtr](../smartptr/)로 변환합니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일 객체를 가리킵니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일 객체를 가리키며, 허용되는 경우 타입 변환을 수행합니다. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 이동 생성합니다. 두 포인터가 동일 모드이면 사실상 두 포인터를 교환합니다. 호출 후 x는 사용 불가능할 수 있습니다. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 다른 타입의 새로운 배열을 생성해 참조된 배열의 타입을 변환합니다. C#에서 지원하지만 C++에서는 지원되지 않는 배열 타입 캐스트가 필요할 때 유용합니다. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | 빈 배열을 초기화합니다. 일부 C# 코드 구문을 변환하는 데 사용됩니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 를 생성하는데, 이는 ptr의 초기값과 소유권 정보를 공유하지만, 무관하고 관리되지 않는 포인터 p를 보유합니다. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 가리키는 객체에 static_cast를 사용해 포인터를 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 어떤 포인터 타입도 [Object](../object/) 포인터로 변환합니다. Pointee_ 타입이 완전할 필요는 없습니다. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | {{Pointee_}} 타입에 대한 [System::TypeInfo](../typeinfo/) 객체를 얻는 단축키입니다. |
| [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) 객체를 파괴합니다. 필요하면 가리키는 객체의 레퍼런스 카운터를 감소시키고 객체를 삭제합니다. |

## 타입 정의

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) 기본 클래스 별칭. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | 자기 타입 별칭. |
| [Pointee_](./pointee_/) | 가리키는 타입. |

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)