---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API 참조
description: 해당 유형에 적용된 모든 사용자 지정 특성을 나타내는 객체를 포함하는 배열을 반환합니다.
type: docs
weight: 586
url: /ko/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const 메서드

해당 유형에 적용된 모든 사용자 지정 특성을 나타내는 객체를 포함하는 배열을 반환합니다.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```
## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const 메서드

해당 유형에 적용된 특정 특성을 나타내는 객체를 포함하는 배열을 반환합니다.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 검색할 특성의 유형입니다. |
| inherit | **bool** | 상속된 특성도 검색할지 여부를 나타냅니다. |

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)