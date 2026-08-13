---
title: TypeInfoPtr
second_title: Aspose.Slides for C++ API 레퍼런스
description: "TypeInfo 클래스 인스턴스에 대한 포인터를 위한 래퍼입니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오."
type: docs
weight: 1951
url: /ko/system/typeinfoptr/
---
## TypeInfoPtr 구조체


포인터가 가리키는 [TypeInfo](../typeinfo/) 클래스 인스턴스에 대한 래퍼. 이 타입은 스택에 할당하고 값 또는 참조에 의해 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
class TypeInfoPtr
```

## 메서드

| Method | Description |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | [TypeInfo](../typeinfo/) 객체에 대한 원시 포인터를 반환합니다. |
|  [TypeInfoPtr](./typeinfoptr/)() | 기본 생성자. |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | 생성자. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | 생성자. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | 생성자. |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | 생성자. |
|  [~TypeInfoPtr](./~typeinfoptr/)() | 소멸자. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)