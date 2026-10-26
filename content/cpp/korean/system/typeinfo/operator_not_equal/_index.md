---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재와 지정된 TypeInfo 객체가 서로 같지 않은지 확인합니다.
type: docs
weight: 456
url: /ko/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const method

현재와 지정된 [TypeInfo](../) 객체가 서로 같지 않은지 확인합니다.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 비교할 [TypeInfo](../) 객체 |

### 반환 값

객체의 해시가 같지 않으면 True, 그렇지 않으면 - false

## TypeInfo::operator!=(std::nullptr_t) const method

현재 [TypeInfo](../) 객체가 null 객체가 아닌지, 즉 어떤 타입을 나타내는지 확인합니다.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### 반환 값

현재 [TypeInfo](../) 객체가 null 객체가 아니면 True, 그렇지 않으면 - false

## 참고

* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)