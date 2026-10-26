---
title: GetUnderlyingType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 nullable 형식의 기본 형식 인수를 반환합니다.
type: docs
weight: 1
url: /ko/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo&) 메서드

특정 nullable 형식의 기본 형식 인수를 반환합니다.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | 닫힌 제네릭 nullable 형식을 설명하는 System.Type 개체입니다. |

### 반환값

nullableType 매개변수가 닫힌 제네릭 nullable 형식인 경우 해당 nullableType 매개변수의 형식 인수; 그렇지 않으면 null

## 참조

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [NullableUtils](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)