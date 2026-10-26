---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 열거형에서 지정된 이름을 가진 열거형 상수의 값을 박싱합니다. 열거형 상수 이름을 지정하는 문자열을 해석할 때 대소문자를 무시할지 여부를 지정하는 매개변수입니다.
type: docs
weight: 53
url: /ko/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) 메서드

지정된 열거형에 있는 열거형 상수의 값을 지정된 이름으로 박싱합니다. 문자열로 지정된 열거형 상수 이름을 해석할 때 대소문자를 무시할지 여부를 지정하는 매개변수입니다.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 열거형의 타입을 지정합니다 |
| str | const [String](../../string/)\& | 박싱할 값의 열거형 상수 이름 |
| ignoreCase | **bool** | 열거형 상수 이름을 나타내는 문자열을 해석할 때 대소문자를 무시할지 지정합니다 |

### Return Value

지정된 열거형 상수의 박싱된 값을 나타내는 객체에 대한 공유 포인터

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) 메서드

지정된 열거형에 있는 열거형 상수의 값을 지정된 이름으로 박싱합니다.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 열거형의 타입을 지정합니다 |
| str | const [String](../../string/)\& | 박싱할 값의 열거형 상수 이름 |

### Return Value

지정된 열거형 상수의 박싱된 값을 나타내는 객체에 대한 공유 포인터

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Object](../../object/)
* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [String](../../string/)
* 클래스 [BoxedValueBase](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)