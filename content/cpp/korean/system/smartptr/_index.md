---
title: SmartPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: "힙에 할당되는 타입을 감싸는 포인터 클래스입니다. Object를 상속하는 클래스의 메모리를 관리하는 데 사용합니다. 이 포인터 타입은 침투 포인터 세맨틱스를 따릅니다. 레퍼런스 카운터는 Object 자체에 저장되거나 Object 인스턴스와 긴밀히 연결된 카운터 구조에 저장됩니다. 어떤 경우든 SmartPtr 인스턴스는 생성 방식에 관계없이 단일 소유 그룹을 형성하며, 이는 std::shared_ptr 클래스의 동작과 다릅니다. 동일한 객체에 대한 공유 참조를 보유하고 있는 다른 SmartPtr 인스턴스가 존재한다면 원시 포인터를 SmartPtr로 변환하는 것은 안전합니다. SmartPtr 클래스 인스턴스는 공유 포인터와 약한 포인터 두 상태 중 하나가 될 수 있습니다. 객체를 살아 있게 유지하려면 공유 참조 카운트가 양수이어야 합니다. 약한 포인터와 공유 포인터 모두 대상 객체에 접근(메서드 호출, 필드 읽기·쓰기 등)할 수 있지만, 약한 포인터는 공유 포인터의 레퍼런스 카운팅에 참여하지 않습니다. 마지막 'shared' SmartPtr 포인터가 파괴될 때 객체가 삭제됩니다. 따라서 객체 생성 또는 파괴 중에 다른 공유 SmartPtr 포인터가 존재하지 않을 경우 이런 일이 발생하지 않도록 해야 합니다. 이 문제를 해결하려면 C++ 코드에서는 System::Object::ThisProtector 감시 객체를, C# 코드에서는 CppCTORSelfReference 또는 CppSelfReference 속성을 사용하십시오. 또한 C++ 코드에서는 System::WeakPtr 포인터 클래스 또는 System::SmartPtrMode::Weak 포인터 모드를, C# 코드에서는 CppWeakPtr 속성을 사용해 순환 참조를 끊어야 합니다. 'shared' 포인터를 사용해 두 개 이상의 객체가 서로를 참조하면 절대 삭제되지 않습니다. 런타임에 포인터 타입(약하거나 공유)을 전환해야 하면 System::SmartPtr<T>::set_Mode() 메서드 또는 System::DynamicWeakPtr 클래스를 사용하십시오. SmartPtr 클래스는 가상 메서드를 포함하지 않습니다. 자체 메모리 관리 전략을 만들 때만 상속해야 합니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터이며, 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다."
type: docs
weight: 1236
url: /ko/system/smartptr/
---
## SmartPtr 클래스

힙에 할당되는 타입을 감싸는 포인터 클래스입니다. [Object](../object/)를 상속하는 클래스의 메모리를 관리하는 데 사용합니다. 이 포인터 타입은 침투 포인터 세맨틱스를 따릅니다. 레퍼런스 카운터는 [Object](../object/) 자체에 저장되거나 [Object](../object/) 인스턴스와 긴밀히 연결된 카운터 구조에 저장됩니다. 어떤 경우든 [SmartPtr](./) 인스턴스는 생성 방식과 관계없이 단일 소유 그룹을 형성하며, 이는 std::shared_ptr 클래스의 동작과 다릅니다. 같은 객체에 대한 공유 참조를 보유하고 있는 다른 [SmartPtr](./) 인스턴스가 존재한다면, 원시 포인터를 [SmartPtr](./)로 변환하는 것은 안전합니다. [SmartPtr](./) 클래스 인스턴스는 공유 포인터와 약한 포인터 두 상태 중 하나일 수 있습니다. 객체를 살아 있게 유지하려면, 해당 객체에 대한 공유 참조 카운트가 양수여야 합니다. 약한 포인터와 공유 포인터 모두 대상 객체에 접근(메서드 호출, 필드 읽기·쓰기 등)할 수 있지만, 약한 포인터는 공유 포인터의 레퍼런스 카운팅에 참여하지 않습니다. [Object](../object/)는 마지막 'shared' [SmartPtr](./) 포인터가 파괴될 때 삭제됩니다. 따라서 객체 생성이나 파괴와 같이 다른 공유 [SmartPtr](./) 포인터가 존재하지 않을 때는 이런 일이 발생하지 않도록 해야 합니다. 이 문제를 해결하려면 System::Object::ThisProtector 감시 객체(C++ 코드) 또는 CppCTORSelfReference·CppSelfReference 속성(C# 코드) 을 사용하십시오. 마찬가지로 [System::WeakPtr](../weakptr/) 포인터 클래스 또는 [System::SmartPtrMode::Weak](../smartptrmode/) 포인터 모드(C++ 코드) 또는 CppWeakPtr 속성(C# 코드)을 사용해 순환 참조를 끊어야 합니다. 'shared' 포인터를 사용해 두 개 이상의 객체가 서로를 참조하면, 절대 삭제되지 않습니다. 런타임에 포인터 타입(약하거나 공유)를 전환해야 하면 [System::SmartPtr<T>::set_Mode()](./set_mode/) 메서드 또는 [System::DynamicWeakPtr](../dynamicweakptr/) 클래스를 사용하십시오. [SmartPtr](./) 클래스는 가상 메서드를 포함하지 않습니다. 자신만의 메모리 관리 전략을 만들고자 할 때만 상속해야 합니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터입니다. 스택에 할당하고 함수에 값이나 const 레퍼런스로 전달해야 합니다.

```cpp
template<class T>class SmartPtr
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 포인터가 가리키는 객체의 타입. [System::Object](../object/)이거나 그 하위 클래스여야 합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| auto [begin](./begin/)() | 하위 컬렉션의 [begin()](./begin/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [begin()](./begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [begin](./begin/)() const | 하위 컬렉션의 [begin()](./begin/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [begin()](./begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | 포인터를 자체 타입으로 변환합니다. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | static_cast를 사용해 포인터를 기본 타입으로 변환합니다. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 변환합니다. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 변환합니다. |
| auto [cbegin](./cbegin/)() const | 하위 컬렉션의 [cbegin()](./cbegin/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [cbegin()](./cbegin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [cend](./cend/)() const | 하위 컬렉션의 [cend()](./cend/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [cend()](./cend/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | const_cast를 사용해 포인터를 다른 타입으로 변환합니다. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | dynamic_cast를 사용해 포인터를 다른 타입으로 변환합니다. |
| auto [end](./end/)() | 하위 컬렉션의 [end()](./end/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [end()](./end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [end](./end/)() const | 하위 컬렉션의 [end()](./end/) 메서드에 접근하는 accessor입니다. SmartPtr_이 [end()](./end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [Pointee_](./pointee_/) * [get](./get/)() const | 가리키는 객체를 반환합니다. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | 포인터 모드를 반환합니다. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | 가리키는 객체를 반환하지만, 포인터가 공유 모드인지 확인합니다. |
| int [get_shared_count](./get_shared_count/)() const | 참조된 객체에 존재하는 공유 포인터 수(현재 포인터 포함)를 반환합니다. 현재 포인터가 공유 모드인지 확인합니다. |
| int [GetHashCode](./gethashcode/)() const | 가리키는 객체에서 [GetHashCode()](./gethashcode/)를 호출합니다. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | 현재 참조된 객체를 반환합니다(없으면 예외 발생). |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | 가리키는 객체를 반환합니다(없으면 nullptr). [get()](./get/)와 동일합니다. |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | 참조된 객체를 반환합니다. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | 가리키는 객체를 반환합니다(없으면 nullptr). [get()](./get/)와 동일합니다. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 가리키는 객체가 특정 타입 또는 그 파생 타입인지 확인합니다. C#의 'is' 의미를 따릅니다. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | 포인터가 별칭 생성자를 통해 만든 소유 객체와 다른 객체를 가리키는지 확인합니다. |
| **bool** [IsShared](./isshared/)() const | 포인터가 공유 모드인지 확인합니다. |
| **bool** [IsWeak](./isweak/)() const | 포인터가 약한 모드인지 확인합니다. |
| explicit  [operator bool](./operator_bool/)() const | 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!](./operator_not/)() const | 포인터가 null인지 확인합니다. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | 가리키는 객체에 대한 레퍼런스를 반환합니다. 포인터가 null이 아닌지 확인합니다. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | 참조된 객체의 멤버에 접근할 수 있게 합니다. |
| **bool** [operator<](./operator_less/)(Y *) const | [SmartPtr](./) 클래스에 대해 less-compare 의미를 제공합니다. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | [SmartPtr](./) 클래스에 대해 less-compare 의미를 제공합니다. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | [SmartPtr](./) 객체를 이동 대입합니다. x는 사용할 수 없게 됩니다. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | [SmartPtr](./) 객체를 복사 대입합니다. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | [SmartPtr](./) 객체를 복사 대입합니다. 필요한 타입 변환을 수행합니다. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | 원시 포인터를 [SmartPtr](./) 객체에 할당합니다. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | 포인터 값을 nullptr로 설정합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 포인터가 nullptr를 가리키는지 확인합니다. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | 별칭(별칭 생성자로 만든)을 포인터에서 제거하고, 포인터가 같은 객체를 관리(공유인 경우)하거나 추적(약한 경우)하도록 보장합니다. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | 가리키는 객체를 설정합니다. |
| void [reset](./reset/)() | 포인터를 nullptr를 가리키게 합니다. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | 포인터 모드를 설정합니다. 이는 참조된 객체의 레퍼런스 카운트를 변경할 수 있습니다. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | 가리키는 객체(있는 경우)에서 SetTemplateWeakPtr() 메서드를 호출합니다. |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | 필요한 모드의 [SmartPtr](./) 객체를 생성합니다. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 필요한 모드의 null-pointer [SmartPtr](./) 객체를 생성합니다. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 지정된 객체를 가리키는 [SmartPtr](./) 를 생성하거나, 원시 포인터를 [SmartPtr](./) 로 변환합니다. |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) 객체를 복사 생성합니다. 이후 두 포인터는 같은 객체를 가리킵니다. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) 객체를 복사 생성합니다. 이후 두 포인터는 같은 객체를 가리키며, 허용되는 경우 타입 변환을 수행합니다. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) 객체를 이동 생성합니다. 두 포인터가 동일 모드인 경우 실제로 두 포인터를 교환합니다. 호출 후 x는 사용할 수 없게 될 수 있습니다. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 새로운 다른 타입 배열을 생성하여 참조된 배열의 타입을 변환합니다. C#에서 지원되지만 C++에서는 지원되지 않는 배열 타입 캐스트가 있을 때 유용합니다. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | 빈 배열을 초기화합니다. 일부 C# 코드 구문을 변환하는 데 사용됩니다. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ptr의 초기값과 소유 정보는 공유하지만, 관련 없고 관리되지 않는 포인터 p를 보유하는 [SmartPtr](./)을 생성합니다. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | static_cast를 사용해 포인터를 다른 타입으로 변환합니다. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | 어떤 포인터 타입이든 [Object](../object/)에 대한 포인터로 변환합니다. Pointee_ 타입이 완전할 필요는 없습니다. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Pointee_ 타입에 대한 [System::TypeInfo](../typeinfo/) 객체를 얻는 단축키입니다. |
|  [~SmartPtr](./~smartptr/)() | [SmartPtr](./) 객체를 파괴합니다. 필요하다면 가리키는 객체의 레퍼런스 카운터를 감소시키고 객체를 삭제합니다. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [Pointee_](./pointee_/) | 가리키는 타입. |
| [SmartPtr_](./smartptr_/) | 특수화된 스마트 포인터 타입. |
| [ArrayType](./arraytype/) | Pointee_와 동일합니다(만약 [System::Array](../array/)의 특수화라면), 그렇지 않으면 void입니다. |
| [ValueType](./valuetype/) | 가리키는 배열의 저장 타입. T가 [System::Array](../array/)의 특수화인 경우에만 의미가 있습니다. |

## 관련 항목

* Namespace [System](../)
* Library [Aspose.Slides](../../)