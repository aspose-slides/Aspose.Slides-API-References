---
title: operator==()
second_title: Aspose.Slides for C++ API 참조
description: 현재와 지정된 TypeInfo 객체가 동일한지 확인합니다.
type: docs
weight: 443
url: /ko/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo&) const 메서드

현재 객체와 지정된 [TypeInfo](../) 객체가 동일한지 확인합니다.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| info | const [TypeInfo](../)\\& | 비교할 [TypeInfo](../) 객체 |

### 반환 값

해시가 동일하면 true, 그렇지 않으면 false

## TypeInfo::operator==(std::nullptr_t) const 메서드

현재 [TypeInfo](../) 객체가 null 객체인지 확인합니다. 즉, 어떤 유형도 나타내지 않습니다.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### 반환 값

현재 [TypeInfo](../) 객체가 null 객체이면 true, 그렇지 않으면 false

## 관련 항목

* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)