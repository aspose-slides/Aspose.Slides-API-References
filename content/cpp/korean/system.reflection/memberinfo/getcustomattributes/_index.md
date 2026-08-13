---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 유형에 적용된 모든 사용자 지정 특성을 나타내는 객체 배열을 반환합니다.
type: docs
weight: 66
url: /ko/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo&, bool) const 메서드

현재 객체가 나타내는 유형에 적용된 모든 사용자 지정 특성을 나타내는 객체 배열을 반환합니다.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)& | 찾을 특성의 유형입니다. |
| inherit | **bool** | 상속된 특성도 확인할지 여부입니다. |

## MemberInfo::GetCustomAttributes(bool) const 메서드

현재 객체가 나타내는 유형에 적용된 모든 사용자 지정 특성을 나타내는 객체 배열을 반환합니다.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| inherit | **bool** | 상속된 특성도 확인할지 여부입니다. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)