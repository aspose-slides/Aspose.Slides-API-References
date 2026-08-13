---
title: GetProperties()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 Type의 모든 공개 속성을 반환합니다.
type: docs
weight: 534
url: /ko/system/typeinfo/getproperties/
---
## TypeInfo::GetProperties() const 메서드


현재 Type의 모든 공개 속성을 반환합니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::PropertyInfo>> System::TypeInfo::GetProperties() const
```

## TypeInfo::GetProperties(System::Reflection::BindingFlags) const 메서드


지정된 바인딩 제약을 사용하여 현재 Type의 속성을 검색합니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::PropertyInfo>> System::TypeInfo::GetProperties(System::Reflection::BindingFlags bindingAttr) const
```

## 참조

* 열거형 [BindingFlags](../../../system.reflection/bindingflags/)
* 타입 정의 [ArrayPtr](../../arrayptr/)
* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [PropertyInfo](../../../system.reflection/propertyinfo/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)