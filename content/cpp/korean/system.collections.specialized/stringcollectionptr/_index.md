---
title: StringCollectionPtr
second_title: Aspose.Slides for C++ API 참조
description: 접근 연산자를 가진 문자열 컬렉션 포인터.
type: docs
weight: 40
url: /ko/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr 클래스

접근 연산자가 있는 문자열 컬렉션 포인터.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## 메서드

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 하부 컬렉션의 [begin()](../../system/smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../../system/smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [begin](../../system/smartptr/begin/)() const | 하부 컬렉션의 [begin()](../../system/smartptr/begin/) 메서드에 대한 접근자. SmartPtr_이 [begin()](../../system/smartptr/begin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 포인터를 자체 타입으로 캐스팅합니다. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast를 사용해 포인터를 기본 타입으로 캐스팅합니다. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 캐스팅합니다. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast를 사용해 포인터를 파생 타입으로 캐스팅합니다. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 하부 컬렉션의 [cbegin()](../../system/smartptr/cbegin/) 메서드에 대한 접근자. SmartPtr_이 [cbegin()](../../system/smartptr/cbegin/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [cend](../../system/smartptr/cend/)() const | 하부 컬렉션의 [cend()](../../system/smartptr/cend/) 메서드에 대한 접근자. SmartPtr_이 [cend()](../../system/smartptr/cend/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | const_cast를 사용해 가리키는 객체를 다른 타입으로 캐스팅합니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | dynamic_cast를 사용해 가리키는 객체를 다른 타입으로 캐스팅합니다. |
| auto [end](../../system/smartptr/end/)() | 하부 컬렉션의 [end()](../../system/smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../../system/smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| auto [end](../../system/smartptr/end/)() const | 하부 컬렉션의 [end()](../../system/smartptr/end/) 메서드에 대한 접근자. SmartPtr_이 [end()](../../system/smartptr/end/) 메서드를 가진 특수화 타입인 경우에만 컴파일됩니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 가리키는 객체를 반환합니다. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 포인터 모드를 반환합니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 가리키는 객체를 반환하지만 포인터가 공유 모드임을 단언합니다. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 현재 포인터를 포함한, 참조된 객체에 존재하는 공유 포인터 수를 반환합니다. 포인터가 공유 모드임을 단언합니다. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 가리키는 객체에서 [GetHashCode()](../../system/smartptr/gethashcode/)를 호출합니다. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 현재 참조된 객체(있는 경우)를 반환하거나 예외를 발생시킵니다. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 가리키는 객체를 반환(있는 경우)하거나 nullptr를 반환합니다. [get()](../../system/smartptr/get/)와 동일합니다. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 참조된 객체를 반환합니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 가리키는 객체를 반환(있는 경우)하거나 nullptr를 반환합니다. [get()](../../system/smartptr/get/)와 동일합니다. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 가리키는 객체가 특정 타입 또는 그 하위 타입인지 확인합니다. C#의 'is' 연산자와 동일한 의미를 갖습니다. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 포인터가 소유된 객체가 아닌 다른 객체를 가리키고 있는지 확인합니다(별칭 생성자를 통해 생성된 경우). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 포인터가 공유 모드인지 확인합니다. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 포인터가 약한 모드인지 확인합니다. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 포인터가 null인지 확인합니다. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 가리키는 객체에 대한 참조를 반환합니다. 포인터가 null이 아님을 단언합니다. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 참조된 객체의 멤버에 접근할 수 있게 합니다. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) 클래스에 대해 less-compare 의미를 제공합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) 객체를 이동 할당합니다. x는 사용 불가능해집니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) 객체를 복사 할당합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) 객체를 복사 할당합니다. 필요한 형 변환을 수행합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) 객체에 원시 포인터를 할당합니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 포인터 값을 nullptr로 설정합니다. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 포인터가 nullptr를 가리키는지 확인합니다. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | 접근자 함수입니다. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 별칭 생성자에 의해 만든 별칭을 제거하고, 포인터가 공유 모드이면 관리하고, 약한 모드이면 추적하도록 합니다. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 가리키는 객체를 설정합니다. |
| void [reset](../../system/smartptr/reset/)() | 포인터를 nullptr로 설정합니다. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 포인터 모드를 설정합니다. 참조된 객체의 레퍼런스 카운트를 변경할 수 있습니다. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 가리키는 객체(있는 경우)에서 SetTemplateWeakPtr() 메서드를 호출합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 필요한 모드의 [SmartPtr](../../system/smartptr/) 객체를 생성합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 필요한 모드의 null-pointer [SmartPtr](../../system/smartptr/) 객체를 생성합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 지정된 객체를 가리키는 [SmartPtr](../../system/smartptr/)를 생성하거나 원시 포인터를 [SmartPtr](../../system/smartptr/)로 변환합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리킵니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 복사 생성합니다. 두 포인터는 이후 동일한 객체를 가리킵니다. 허용되는 경우 형 변환을 수행합니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) 객체를 이동 생성합니다. 두 포인터가 같은 모드이면 사실상 교환됩니다. 호출 후 x는 사용 불가능할 수 있습니다. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 다른 타입의 새 배열을 만들면서 참조된 배열 타입을 변환합니다. C#에서 지원하지만 C++에서는 지원되지 않는 배열 형 변환에 유용합니다. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 빈 배열을 초기화합니다. 일부 C# 코드 구문을 변환하는 데 사용됩니다. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 초기 ptr 값과 소유권 정보를 공유하지만, 무관하고 관리되지 않는 포인터 p를 보유하는 [SmartPtr](../../system/smartptr/)를 만들습니다. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | static_cast를 사용해 가리키는 객체를 다른 타입으로 캐스팅합니다. |
|  [StringCollectionPtr](./stringcollectionptr/)() | null 포인터를 생성합니다. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | 특정 컬렉션에 대한 포인터를 생성합니다. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 어떤 포인터 타입이든 [Object](../../system/object/) 포인터로 변환합니다. Pointee_ 타입이 완전하지 않아도 됩니다. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ 타입에 대한 [System::TypeInfo](../../system/typeinfo/) 객체를 얻는 단축 함수입니다. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) 객체를 파괴합니다. 필요 시 가리키는 객체의 레퍼런스 카운터를 감소시키고 객체를 삭제합니다. |
## See Also

* 클래스 [SmartPtr](../../system/smartptr/)
* 네임스페이스 [System::Collections::Specialized](../)
* 라이브러리 [Aspose.Slides](../../)