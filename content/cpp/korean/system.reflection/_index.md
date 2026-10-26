---
title: "System::Reflection"
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 755
url: /ko/system.reflection/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) 클래스는 어셈블리를 설명합니다. 규칙이 C#과 C++ 사이에 크게 다르기 때문에 지원이 제한됩니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터에 래핑하고 해당 포인터를 인수로 함수에 전달하십시오. |
| [AssemblyName](./assemblyname/) | 어셈블리 이름을 정의합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터에 래핑하고 해당 포인터를 인수로 함수에 전달하십시오. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | 실행 중인 어셈블리에서 형식을 등록하기 위한 싱글톤. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | 실행 중인 어셈블리에서 형식을 등록하는 싱글톤의 기본 유형. |
| [ConstructorInfo](./constructorinfo/) | 생성자 메타데이터에 대한 액세스를 제공합니다. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | 모듈의 클래스 중 하나라도 로드에 실패하면 Module.GetTypes 메서드에서 ReflectionTypeLoadException이 발생합니다. 이 클래스를 직접 생성하지 마십시오. 대신 ReflectionTypeLoadException 클래스를 사용하십시오. ReflectionTypeLoadException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | 리플렉션을 통해 호출된 메서드에서 TargetInvocationException이 발생합니다. 이 클래스를 직접 생성하지 마십시오. 대신 TargetInvocationException 클래스를 사용하십시오. TargetInvocationException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [FieldInfo](./fieldinfo/) | 필드의 속성을 찾아보고 필드 메타데이터에 대한 액세스를 제공합니다. |
| [MemberInfo](./memberinfo/) | 멤버에 대한 리플렉션 정보를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터에 래핑하고 해당 포인터를 인수로 함수에 전달하십시오. |
| [MethodBase](./methodbase/) | 메서드에 대한 기본 정보. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터에 래핑하고 해당 포인터를 인수로 함수에 전달하십시오. |
| [MethodInfo](./methodinfo/) | 클래스 메서드에 대한 정보를 나타냅니다. |
| [PropertyInfo](./propertyinfo/) | 속성 정보를 나타냅니다. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [BindingFlags](./bindingflags/) | 멤버와 타입 검색 모드 및 바인딩을 정의합니다. |
| [FieldAttributes](./fieldattributes/) | 리플렉션된 필드 속성. |
| [MemberTypes](./membertypes/) | 각 멤버 유형을 표시합니다. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | 모듈의 클래스 중 하나라도 로드에 실패하면 Module.GetTypes 메서드에서 ReflectionTypeLoadException이 발생합니다. ReflectionTypeLoadException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [TargetInvocationException](./targetinvocationexception/) | 리플렉션을 통해 호출된 메서드에서 TargetInvocationException이 발생합니다. TargetInvocationException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |