---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열거형 타입과 지정된 이름을 가진 열거형 상수 값을 나타내는 객체를 반환합니다.
type: docs
weight: 27
url: /ko/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) 메서드


지정된 열거형 타입과 지정된 이름을 가진 열거형 상수 값을 나타내는 객체를 반환합니다.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 객체는 반환할 열거형 값의 유형을 나타냅니다 |
| str | const [String](../../string/)\& | 열거형 상수의 이름 |
| ignoreCase | **bool** | 열거형 상수 이름을 해석할 때 대소문자를 무시해야 하는지 지정합니다 |

### 반환값

**str**에 지정된 이름을 가진 열거형 상수 값을 나타내는 객체.

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Object](../../object/)
* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [String](../../string/)
* 클래스 [EnumValuesBase](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)