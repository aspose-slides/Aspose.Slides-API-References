---
title: WeakPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: "System::SmartPtr의 서브클래스로, 생성 시 자신을 약한 모드로 설정합니다. 이 클래스는 set_Mode()이 여전히 접근 가능하기 때문에 인스턴스가 항상 약한 모드에 머무른다는 보장을 하지 않습니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터이며, 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다."
type: docs
weight: 1496
url: /ko/system/weakptr/
---
## WeakPtr 클래스

Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 포인티 타입. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 하위 컬렉션의 [begin()](../smartptr/begin/) 메서드에 대한 접근자입니다. SmartPtr_이 [begin()](../smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [begin](../smartptr/begin/)() const | 하위 컬렉션의 [begin()](../smartptr/begin/) 메서드에 대한 접근자입니다. SmartPtr_이 [begin()](../smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 포인터를 해당 타입 자체로 캐스팅합니다. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | static_cast를 사용하여 포인터를 기본 타입으로 캐스팅합니다. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast를 사용하여 포인터를 파생 타입으로 캐스팅합니다. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast를 사용하여 포인터를 파생 타입으로 캐스팅합니다. |
| auto [cbegin](../smartptr/cbegin/)() const | 하위 컬렉션의 [cbegin()](../smartptr/cbegin/) 메서드에 대한 접근자입니다. SmartPtr_이 [cbegin()](../smartptr/cbegin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [cend](../smartptr/cend/)() const | 하위 컬렉션의 [cend()](../smartptr/cend/) 메서드에 대한 접근자입니다. SmartPtr_이 [cend()](../smartptr/cend/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 포인티된 객체에 const_cast를 사용하여 포인터를 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 포인티된 객체에 dynamic_cast를 사용하여 포인터를 다른 타입으로 캐스팅합니다. |
| auto [end](../smartptr/end/)() | 하위 컬렉션의 [end()](../smartptr/end/) 메서드에 대한 접근자입니다. SmartPtr_이 [end()](../smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [end](../smartptr/end/)() const | 하위 컬렉션의 [end()](../smartptr/end/) 메서드에 대한 접근자입니다. SmartPtr_이 [end()](../smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| **bool** [expired](./expired/)() const | 참조된 객체가 이미 삭제되었는지 확인합니다. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 포인티된 객체를 가져옵니다. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 포인터 모드를 가져옵니다. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 포인티된 객체를 가져오지만 포인터가 공유 모드인지 확인합니다. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 참조된 객체에 존재하는 공유 포인터 수를 현재 포인터를 포함하여 가져옵니다. 현재 포인터가 공유 모드인지 확인합니다. |
| [Object](../object/) * [get_weak](./get_weak/)() const | 참조된 객체를 가져오며 포인터가 약한 모드인지 확인합니다. |
| int [GetHashCode](../smartptr/gethashcode/)() const | 포인티된 객체에서 [GetHashCode()](../smartptr/gethashcode/)를 호출합니다. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 현재 참조된 객체를(있다면) 가져오거나 예외를 발생시킵니다. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 포인티된 객체를(있다면) 가져오거나 nullptr를 반환합니다. [get()](../smartptr/get/)와 동일합니다. |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 참조된 객체를 가져옵니다. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 포인티된 객체를(있다면) 가져오거나 nullptr를 반환합니다. [get()](../smartptr/get/)와 동일합니다. |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 포인티된 객체가 특정 타입 또는 그 하위 타입인지 확인합니다. C#의 'is' 의미와 동일합니다. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 포인터가 소유된 객체가 아닌 다른 객체를 가리키는지(별칭 생성자를 통해 생성된) 확인합니다. |
| **bool** [IsShared](../smartptr/isshared/)() const | 포인터가 공유 모드인지 확인합니다. |
| **bool** [IsWeak](../smartptr/isweak/)() const | 포인터가 약한 모드인지 확인합니다. |
| explicit [operator bool](../smartptr/operator_bool/)() const | 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!](../smartptr/operator_not/)() const | 포인터가 null인지 확인합니다. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 포인티된 객체에 대한 레퍼런스를 가져옵니다. 포인터가 null이 아닌지 확인합니다. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 참조된 객체의 멤버에 접근할 수 있습니다. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) 클래스에 대한 less-compare 의미를 제공합니다. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) 클래스에 대한 less-compare 의미를 제공합니다. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | 약한 포인터에 값을 할당합니다. SmartPtr_의 특정 할당 연산자를 호출합니다. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | [SmartPtr](../smartptr/) 객체를 이동 할당합니다. x는 사용 불가능해집니다. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | [SmartPtr](../smartptr/) 객체를 복사 할당합니다. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | [SmartPtr](../smartptr/) 객체를 복사 할당합니다. 필요한 타입 변환을 수행합니다. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | 원시 포인터를 [SmartPtr](../smartptr/) 객체에 할당합니다. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | 포인터 값을 nullptr로 설정합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 약한 포인터가 null인지 확인합니다. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 포인터에서 별칭(별칭 생성자를 통해 생성된)을 제거하고, 포인터가 가리키는 동일한 객체를 (공유인 경우 관리하고, 약한 경우 추적하도록) 보장합니다. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 포인티된 객체를 설정합니다. |
| void [reset](../smartptr/reset/)() | 포인터가 nullptr를 가리키도록 합니다. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 포인터 모드를 설정합니다. 참조된 객체의 레퍼런스 카운트가 변경될 수 있습니다. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 포인티된 객체(있는 경우)에서 SetTemplateWeakPtr() 메서드를 호출합니다. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 필요한 모드의 [SmartPtr](../smartptr/) 객체를 생성합니다. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 필요한 모드의 nullptr [SmartPtr](../smartptr/) 객체를 생성합니다. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 지정된 객체를 가리키는 [SmartPtr](../smartptr/)를 생성하거나 원시 포인터를 [SmartPtr](../smartptr/)로 변환합니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리킵니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리키며, 허용되는 경우 타입 변환을 수행합니다. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) 객체를 이동 생성합니다. 두 포인터가 동일한 모드인 경우 실질적으로 포인터를 교환합니다. 호출 후 x는 사용 불가능할 수 있습니다. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 다른 타입의 새 배열을 생성하여 참조된 배열의 타입을 변환합니다. C#에서 지원하지만 C++에서는 지원되지 않는 배열 타입 캐스트를 처리할 때 유용합니다. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | 빈 배열을 초기화합니다. 일부 C# 코드 구문을 변환하는 데 사용됩니다. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/)을 생성하며, 이는 ptr의 초기값과 소유권 정보를 공유하지만, 관련 없고 관리되지 않는 포인터 p를 보유합니다. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 포인티된 객체에 static_cast를 사용하여 포인터를 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 어떤 포인터 타입이든 [Object](../object/)에 대한 포인터로 변환합니다. Pointee_ 타입이 완전할 필요는 없습니다. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pointee_ 타입에 대한 [System::TypeInfo](../typeinfo/) 객체를 얻기 위한 바로 가기입니다. |
| [WeakPtr](./weakptr/)(std::nullptr_t) | null 포인터를 생성합니다. |
| [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | 주어진 객체에 대한 약한 포인터를 생성합니다. |
| [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | ptr이 가리키는 동일한 포인터를 참조하는 약한 포인터를 생성합니다. |
| [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | x가 가리키는 동일한 포인터를 참조하는 약한 포인터를 생성합니다. |
| [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | 약한 포인터를 복사 생성합니다. |
| [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | 약한 포인터를 복사 생성합니다. |
| [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 약한 포인터를 이동 생성합니다. |
| [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) 객체를 파괴합니다. 필요 시 포인티된 객체의 레퍼런스 카운터를 감소시키고 객체를 삭제합니다. |

## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [SmartPtr_](./smartptr_/) | 해당 [SmartPtr](../smartptr/) 클래스에 대한 별칭입니다. |
| [WeakPtr_](./weakptr_/) | self 타입에 대한 별칭입니다. |
| [Pointee_](./pointee_/) | 포인티 타입입니다. |

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)