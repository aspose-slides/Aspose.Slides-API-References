---
title: HashSetPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: HashSet 참조를 유지하기 위한 포인터입니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터입니다. 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다.
type: docs
weight: 235
url: /ko/system.collections.generic/hashsetptr/
---
## HashSetPtr 클래스

Pointer to keep [HashSet](../hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## 메서드

| Method | 설명 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 하위 컬렉션의 [begin()](../../system/smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../../system/smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [begin](../../system/smartptr/begin/)() const | 하위 컬렉션의 [begin()](../../system/smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../../system/smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 포인터를 자체 타입으로 캐스팅합니다. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast를 사용하여 포인터를 기본 타입으로 캐스팅합니다. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast를 사용하여 포인터를 파생 타입으로 캐스팅합니다. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast를 사용하여 포인터를 파생 타입으로 캐스팅합니다. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 하위 컬렉션의 [cbegin()](../../system/smartptr/cbegin/) 메서드에 대한 접근자. SmartPtr_이 [cbegin()](../../system/smartptr/cbegin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [cend](../../system/smartptr/cend/)() const | 하위 컬렉션의 [cend()](../../system/smartptr/cend/) 메서드에 대한 접근자. SmartPtr_이 [cend()](../../system/smartptr/cend/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 포인터가 가리키는 객체에 const_cast를 사용하여 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 포인터가 가리키는 객체에 dynamic_cast를 사용하여 다른 타입으로 캐스팅합니다. |
| auto [end](../../system/smartptr/end/)() | 하위 컬렉션의 [end()](../../system/smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../../system/smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [end](../../system/smartptr/end/)() const | 하위 컬렉션의 [end()](../../system/smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../../system/smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 가리키는 객체를 가져옵니다. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 포인터 모드를 가져옵니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 가리키는 객체를 가져오지만, 포인터가 공유 모드임을 검증합니다. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 현재 포인터를 포함하여 참조된 객체에 존재하는 공유 포인터 수를 가져옵니다. 현재 포인터가 공유 모드임을 검증합니다. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 가리키는 객체에 [GetHashCode()](../../system/smartptr/gethashcode/)를 호출합니다. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 현재 참조된 객체를 가져오며(없는 경우 예외 발생). |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 가리키는 객체를 가져오며(없는 경우 nullptr). [get()](../../system/smartptr/get/)와 동일합니다. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 참조된 객체를 가져옵니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 가리키는 객체를 가져오며(없는 경우 nullptr). [get()](../../system/smartptr/get/)와 동일합니다. |
|  [HashSetPtr](./hashsetptr/)() | 널 포인터 생성자. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | 복사 생성자. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 가리키는 객체가 특정 타입이나 그 자식 타입인지 확인합니다. C# 'is' 의미를 따릅니다. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 포인터가 소유된 객체가 아닌 다른 객체를 가리키는지 확인합니다(별칭 생성자로 생성된 경우). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 포인터가 공유 모드인지 확인합니다. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 포인터가 약한(weak) 모드인지 확인합니다. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 포인터가 null인지 확인합니다. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 가리키는 객체에 대한 참조를 가져옵니다. 포인터가 null이 아님을 검증합니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 참조된 객체의 멤버에 접근할 수 있게 합니다. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) 객체에 대해 이동 할당을 수행합니다. x는 사용 불가능해집니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) 객체에 대해 복사 할당을 수행합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) 객체에 대해 복사 할당을 수행합니다. 필요한 타입 변환을 수행합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 원시 포인터를 [SmartPtr](../../system/smartptr/) 객체에 할당합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 포인터 값을 nullptr로 설정합니다. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 포인터가 nullptr를 가리키는지 확인합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 포인터에서 별칭을 제거합니다(별칭 생성자로 생성됨). 포인터가 가리키는 동일한 객체를 (공유인 경우 관리하고, 약한 경우 추적하도록) 보장합니다. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 가리키는 객체를 설정합니다. |
| void [reset](../../system/smartptr/reset/)() | 포인터가 nullptr를 가리키도록 합니다. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 포인터 모드를 설정합니다. 참조된 객체의 참조 카운트를 변경할 수 있습니다. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 가리키는 객체에 (있는 경우) SetTemplateWeakPtr() 메서드를 호출합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 필요 모드의 [SmartPtr](../../system/smartptr/) 객체를 생성합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 필요 모드의 널 포인터 [SmartPtr](../../system/smartptr/) 객체를 생성합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 지정된 객체를 가리키는 [SmartPtr](../../system/smartptr/)를 생성하거나, 원시 포인터를 [SmartPtr](../../system/smartptr/)으로 변환합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리킵니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리킵니다. 허용되는 경우 타입 변환을 수행합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 이동 생성합니다. 두 포인터가 동일한 모드인 경우 실질적으로 두 포인터를 교환합니다. 호출 후 x는 사용 불가능할 수 있습니다. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 다른 타입의 새 배열을 생성하여 참조된 배열의 타입을 변환합니다. C#에서는 지원하지만 C++에서는 지원되지 않는 배열 타입 캐스트가 있을 때 유용합니다. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 빈 배열을 초기화합니다. 일부 C# 코드 구조를 변환하는 데 사용됩니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 를 구성합니다. 이는 ptr의 초기값과 소유권 정보를 공유하지만, 관련 없고 관리되지 않는 포인터 p를 보유합니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 가리키는 객체에 static_cast를 사용하여 포인터를 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 어떤 포인터 타입이든 [Object](../../system/object/) 포인터로 변환합니다. Pointee_ 타입이 완전할 필요는 없습니다. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ 타입에 대한 [System::TypeInfo](../../system/typeinfo/) 객체를 얻기 위한 단축키입니다. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) 객체를 파괴합니다. 필요시 가리키는 객체의 참조 카운터를 감소시키고 객체를 삭제합니다. |

## 참조

* 클래스 [SmartPtr](../../system/smartptr/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)