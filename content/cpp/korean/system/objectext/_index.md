---
title: ObjectExt
second_title: Aspose.Slides for C++ API 레퍼런스
description: C# Object 메서드를 에뮬레이트하는 정적 메서드를 제공하며, 이는 Object가 아닌 C++ 유형(문자열, 숫자 등)에서 호출됩니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 1145
url: /ko/system/objectext/
---
## ObjectExt 클래스

비-Object C++ 유형(문자열, 숫자 등)에 대해 호출되는 C# [Object](../object/) 메서드를 에뮬레이트하는 정적 메서드를 제공합니다. 이 타입은 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class ObjectExt : public System::ObjectType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | 배열 기본값을 변환합니다( C#은 암시적으로 수행하지만 C++에서는 명시적으로 수행하지 않는 것으로 보입니다). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Object](../object/) 로 변환하기 위해 값 유형을 박싱합니다. 열거형 타입에 대한 구현입니다. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Object](../object/) 로 변환하기 위해 값 유형을 박싱합니다. 열거형이 아닌 타입에 대한 구현입니다. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Object](../object/) 로 변환하기 위해 [Nullable](../nullable/) 타입을 박싱합니다. |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | 문자열 값을 박싱합니다. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | [Object](../object/) 로 전파되도록 열거형 타입을 박싱합니다. |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | 널이 아닌 타입에 대한 '??' 연산자 변환 구현입니다. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | 널 가능한 타입에 대한 '??' 연산자 변환 구현입니다. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | '??=' 연산자 변환 구현입니다. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | 널이 아닌 타입에 대한 '??' 연산자 변환 구현입니다. RT2가 RT1로 변환 가능한 경우에 대한 오버로드입니다. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) 호출을 C++ 모든 타입에서 동작하도록 대체합니다. 스마트 포인터 타입에 대한 오버로드입니다. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | C# [Object.Equals](../object/equals/) 호출을 C++ 모든 타입에서 동작하도록 대체합니다. 구조체 타입에 대한 오버로드입니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) 호출을 C++ 모든 타입에서 동작하도록 대체합니다. 스칼라 타입에 대한 오버로드입니다. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | C# [Object.Equals](../object/equals/) 호출을 C++ 모든 타입에서 동작하도록 대체합니다. 문자열 리터럴과 문자열 비교에 대한 오버로드입니다. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | [GetHashCode()](./gethashcode/) 호출을 구현합니다; [Object](../object/) 하위 클래스와 무관한 타입 모두에서 동작합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() 변환을 구현합니다. 스마트 포인터에 대한 오버로드입니다. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() 변환을 구현합니다. 구조체에 대한 오버로드입니다. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() 변환을 구현합니다. 예외에 대한 오버로드입니다. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() 변환을 구현합니다. 기본 타입에 대한 오버로드입니다. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() 변환을 구현합니다. [Nullable](../nullable/) 타입에 대한 오버로드입니다. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. 기본 타입에 대한 오버로드입니다. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. 열거형에 대한 오버로드입니다. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. 구조체와 포인터에 대한 오버로드입니다. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. [Nullable](../nullable/)에 대한 오버로드입니다. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. MulticastDelegate에 대한 오버로드입니다. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. 구조체와 포인터에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | typeof() 변환을 구현합니다. 문자열 타입에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드입니다. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 'is' 연산자 변환을 구현합니다. 박싱 가능한(값) 타입에 대한 특수화이며, 이는 정확히 그 타입임을 의미합니다. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' 연산자 변환을 구현합니다. 'final' 클래스를 위해 최적화된 포인터 타입에 대한 특수화입니다. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' 연산자 변환을 구현합니다. 포인터 타입에 대한 특수화입니다. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' 연산자 변환을 구현합니다. 값 타입에 대한 특수화입니다. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' 연산자 변환을 구현합니다. 변환 불가능한 타입에 대한 특수화입니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' 연산자 변환을 구현합니다. 포인터 타입에 대한 특수화입니다. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 'is' 연산자 변환을 구현합니다. 예외 래퍼 타입에 대한 특수화입니다. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 연산자 변환을 구현합니다. Nullable 타입에 대한 특수화입니다. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 연산자 변환을 구현합니다. == 연산자가 정의된 박싱 가능한 타입에 대한 특수화입니다. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 연산자 변환을 구현합니다. == 연산자가 정의되지 않은 박싱 가능한 타입에 대한 특수화입니다. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 'is' 연산자 변환을 구현합니다. 인터페이스에 박싱된 값 타입에 대한 특수화입니다. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' 연산자 변환을 구현합니다. 열거형 타입에 대한 특수화입니다. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 'is' 연산자 변환을 구현합니다. 약한 포인터와 비교되는 열거형 타입에 대한 특수화입니다. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 'is' 연산자 변환을 구현합니다. [Nullable](../nullable/) 타입에 대한 특수화입니다. |
| static **bool** [Is](./is/)(const char16_t *) | 'is' 연산자 변환을 구현합니다. 문자열 리터럴에 대한 특수화입니다. |
| static **bool** [Is](./is/)(**int32_t**) | 'is' 연산자 변환을 구현합니다. 정수 리터럴에 대한 특수화입니다. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 객체가 박싱된 값인지 확인합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/)를 알 수 없는 타입으로 변환합니다. 스마트 포인터 타입과 박싱된 값 상황을 모두 처리합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/)를 알 수 없는 타입으로 변환합니다. 스마트 포인터 타입과 박싱된 값 상황을 모두 처리합니다. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString 메서드를 C++ 모든 타입에서 동작하도록 대체합니다. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) 로 변환한 후 값 타입을 언박싱합니다. 열거형 타입에 대한 구현입니다. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) 로 변환한 후 값 타입을 언박싱합니다. 열거형이 아니고 nullable이 아닌 타입에 대한 구현입니다. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) 로 변환한 후 값 타입을 언박싱합니다. 열거형이 아니고 nullable이 아닌 타입에 대한 구현입니다. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | 열거형 타입을 정수형으로 언박싱합니다. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | 열거형 타입을 변환합니다. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 문자열 값을 언박싱합니다. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 박싱된 값에서 문자열을 언박싱합니다. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 객체를 nullable 타입으로 언박싱합니다. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 알 수 없는 타입 객체가 nullptr인지 확인합니다. 스칼라가 아닌 타입에 대한 오버로드입니다. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 알 수 없는 타입 객체가 nullptr인지 확인합니다. 스칼라 타입에 대한 오버로드입니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | 알 수 없는 타입을 [Object](../object/) 로 변환합니다. 스마트 포인터 타입과 값 타입 상황을 모두 처리합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | 알 수 없는 타입을 [Object](../object/) 로 변환합니다. 스마트 포인터 타입과 값 타입 상황을 모두 처리합니다. |

## 관련 항목

* 클래스 [ObjectType](../objecttype/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)