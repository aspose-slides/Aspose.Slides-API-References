---
title: GetValueOf()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 이름을 가진 열거형 상수의 박싱된 값을 반환합니다.
type: docs
weight: 53
url: /ko/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const 메서드


지정된 이름을 가진 열거형 상수의 박싱된 값을 반환합니다.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 열거형 상수의 이름 |
| ignoreCase | **bool** | 열거형 상수 이름을 해석할 때 대소문자를 무시할지 여부를 지정합니다 |

### 반환값

**str**에 지정된 이름을 가진 열거형 상수의 박싱된 값을 반환합니다.

## EnumValues::GetValueOf(long) const 메서드


지정된 값을 가진 열거형 상수의 박싱된 값을 반환합니다.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| val | long | 열거형 상수의 값 |

### 반환값

**str**에 지정된 값을 가진 열거형 상수의 박싱된 값을 반환합니다.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Object](../../object/)
* 클래스 [String](../../string/)
* 클래스 [EnumValues](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)