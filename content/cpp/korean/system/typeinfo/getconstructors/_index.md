---
title: GetConstructors()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 BindingFlags를 사용하여 현재 Type에 정의된 생성자를 검색합니다.
type: docs
weight: 365
url: /ko/system/typeinfo/getconstructors/
---
## TypeInfo::GetConstructors(System::Reflection::BindingFlags) const 메서드

지정된 BindingFlags를 사용하여 현재 Type에 정의된 생성자를 검색합니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::ConstructorInfo>> System::TypeInfo::GetConstructors(System::Reflection::BindingFlags bindingAttr) const
```
## TypeInfo::GetConstructors() const 메서드

현재 Type에 정의된 모든 public 생성자를 반환합니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::ConstructorInfo>> System::TypeInfo::GetConstructors() const
```
## 참조

* 열거형 [BindingFlags](../../../system.reflection/bindingflags/)
* 타입정의 [ArrayPtr](../../arrayptr/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [ConstructorInfo](../../../system.reflection/constructorinfo/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)