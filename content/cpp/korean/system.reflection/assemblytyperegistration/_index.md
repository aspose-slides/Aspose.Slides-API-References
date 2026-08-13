---
title: AssemblyTypeRegistration
second_title: Aspose.Slides for C++ API 레퍼런스
description: 실행 어셈블리에서 타입을 등록하기 위한 싱글톤.
type: docs
weight: 27
url: /ko/system.reflection/assemblytyperegistration/
---
## AssemblyTypeRegistration 클래스

Singleton을 등록하기 위해 실행 어셈블리에서 타입을 등록하는 싱글톤.

```cpp
template<typename T>class AssemblyTypeRegistration : public System::Reflection::AssemblyTypeRegistrationBase
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 등록할 타입. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)() | 싱글톤을 생성하여 실행 어셈블리에서 타입을 등록합니다. |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)(const [SharedPtr](../../system/sharedptr/)\<[Assembly](../assembly/)\>\&) | 싱글톤을 생성하여 지정된 어셈블리에서 타입을 등록합니다. |

## 참조

* 클래스 [AssemblyTypeRegistrationBase](../assemblytyperegistrationbase/)
* 네임스페이스 [System::Reflection](../)
* 라이브러리 [Aspose.Slides](../../)