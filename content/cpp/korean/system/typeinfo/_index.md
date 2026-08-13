---
title: TypeInfo
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 유형을 나타내며 해당 유형에 대한 정보를 제공합니다.
type: docs
weight: 1379
url: /ko/system/typeinfo/
---
## TypeInfo 클래스

특정 유형을 나타내며 해당 유형에 대한 정보를 제공합니다.

```cpp
class TypeInfo
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | 지정된 속성을 유형의 속성 목록에 추가합니다. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | 유형 T에 대한 기본 생성자를 설정합니다. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | 클래스 인스턴스를 생성하는 함수 객체를 사용하여 기본 생성자를 설정합니다. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | 지정된 멤버를 유형의 멤버 목록에 추가합니다. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | 다중 Boxed* 클래스가 공유하도록 **BoxedValue** 유형에 대한 고유한 [TypeInfo](./) 구조를 제공합니다. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | 구현되지 않음. 현재 객체가 선언된 어셈블리에 대한 포인터를 반환합니다. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | 구현되지 않음. 현재 객체가 나타내는 유형의 어셈블리 이름을 포함한 전체 지정 이름을 반환합니다. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | 기본 유형 설명자를 반환합니다. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | 현재 Type 객체에 아직 구체적인 유형으로 대체되지 않은 형식 매개변수가 있는지 여부를 나타내는 값을 가져옵니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | 지정된 이름을 가진 멤버 목록을 가져옵니다. |
| [String](../string/) [get_FullName](./get_fullname/)() const | 현재 객체가 나타내는 유형의 전체 지정 이름(어셈블리 이름 제외)을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | 이 유형에 대한 일반 형식 인수 배열을 가져옵니다. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Type이 추상이며 반드시 재정의해야 하는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsArray](./get_isarray/)() const | 유형이 배열인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsClass](./get_isclass/)() const | Type이 클래스 또는 대리자인지(값 형식이나 인터페이스가 아닌) 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsEnum](./get_isenum/)() const | 현재 Type이 열거형을 나타내는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | 현재 Type이 다른 일반 유형을 구성할 수 있는 일반 유형 정의를 나타내는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Type이 인터페이스인지(클래스나 값 형식이 아닌) 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsSealed](./get_issealed/)() const | Type이 sealed로 선언되었는지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Type이 값 형식인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Type이 어셈블리 외부 코드에서 접근할 수 있는지 여부를 나타내는 값을 가져옵니다. |
| [String](../string/) [get_Name](./get_name/)() const | 현재 객체가 나타내는 유형의 이름을 반환합니다. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Type의 네임스페이스를 가져옵니다. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | 지정된 배열의 유형과 일치하는 매개변수를 가진 public 인스턴스 생성자를 검색합니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 지정된 BindingFlags를 사용하여 현재 Type에 정의된 생성자를 검색합니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | 현재 Type에 정의된 모든 public 생성자를 반환합니다. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | 지정된 유형을 가진 사용자 정의 속성을 검색하고 현재 객체가 나타내는 유형에 적용된 것을 찾습니다. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | 유형에 적용된 모든 사용자 정의 속성을 나타내는 객체 배열을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | 유형에 적용된 특정 속성을 나타내는 객체 배열을 반환합니다. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | 구현되지 않음. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 지정된 바인딩 제약을 사용하여 지정된 필드를 검색합니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 지정된 바인딩 제약을 사용하여 현재 Type에 정의된 필드를 검색합니다. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | 이 유형에 대한 일반 형식 인수 배열을 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const | 이 인스턴스와 연관된 해시 코드를 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | 현재 Type이 구현하거나 상속한 모든 인터페이스를 가져옵니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | 지정된 이름을 가진 멤버 목록을 가져옵니다. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | 지정된 이름을 가진 메서드를 가져옵니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | 현재 Type의 모든 public 속성을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 지정된 바인딩 제약을 사용하여 현재 Type의 속성을 검색합니다. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | 템플릿 매개변수 유형 설명자를 가져옵니다. |
| **uint32_t** [Hash](./hash/)() const | 현재 객체가 나타내는 유형과 연관된 해시 값을 반환합니다. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | 지정된 유형의 인스턴스를 현재 유형의 변수에 할당할 수 있는지 여부를 판단합니다. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | 구현되지 않음. 지정된 유형 또는 파생 유형의 하나 이상의 속성이 이 멤버에 적용되었는지 여부를 나타냅니다. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 지정된 객체가 현재 유형의 인스턴스인지 여부를 판단합니다. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | 현재 객체가 나타내는 유형이 지정된 클래스의 서브클래스인지 여부를 판단합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | 현재와 지정된 [TypeInfo](./) 객체가 동일하지 않은지 여부를 판단합니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 현재 [TypeInfo](./) 객체가 null 객체가 아니며, 즉 어떤 유형을 나타내는지 여부를 판단합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | 현재와 지정된 [TypeInfo](./) 객체가 동일한지 여부를 판단합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 현재 [TypeInfo](./) 객체가 null 객체이며, 즉 어떠한 유형도 나타내지 않는지 여부를 판단합니다. |
| void [reset](./reset/)() | [TypeInfo](./)를 null로 설정합니다. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Type이 값 형식인지 여부를 나타내는 값을 설정합니다. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | 기본 유형 설명자를 설정합니다. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | 템플릿 매개변수 유형 설명자를 설정합니다. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | 지정된 문자열에 대한 해시를 계산합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 유형의 이름을 포함하는 문자열을 반환합니다. |
| static const [TypeInfo](./)\& [Type](./type/)() | [TypeInfo](./) 객체를 반환하며, 이는 [TypeInfo](./) 클래스를 나타냅니다. |
|  [TypeInfo](./typeinfo/)() | 기본 생성자(설정된 유형이 없음). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | null 객체 생성자(설정된 유형이 없음). |
|  [TypeInfo](./typeinfo/)(const char_t *) | 생성자. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | 생성자. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | 생성자. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [EmptyType](./emptytype/) | 빈 [TypeInfo](./) 목록을 나타내는 상수. |
| static [EmptyTypes](./emptytypes/) | 빈 [TypeInfo](./) 목록을 나타내는 상수. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | 유형을 생성하는 함수 포인터. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)