---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 타입을 가지고 현재 객체가 나타내는 타입에 적용된 커스텀 속성을 검색합니다.
type: docs
weight: 573
url: /ko/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const 메서드

지정된 타입을 가지고 현재 객체가 나타내는 타입에 적용된 커스텀 속성을 검색합니다.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 검색할 속성의 유형을 나타내는 [TypeInfo](../) 객체에 대한 상수 참조 |

### 반환 값

검색 기준과 일치하는 속성이 없으면 null 포인터이며, 찾은 속성을 나타내는 객체에 대한 포인터를 반환합니다.

## 참고

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)