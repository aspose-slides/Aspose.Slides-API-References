---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 타입에 적용된 지정된 유형의 사용자 정의 특성을 반환합니다.
type: docs
weight: 1
url: /ko/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) 메서드

지정된 타입에 적용된 지정된 유형의 사용자 정의 특성을 반환합니다.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 검색될 특성의 타입 |
| attributeType | const [TypeInfo](../../typeinfo/)\& | 검색할 특성의 타입 |

### 반환값

검색된 특성 또는 지정된 타입에 해당 특성이 없을 경우 null을 반환합니다.

## 참고

* Typedef [ptr](../../object/ptr/)
* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Attribute](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)