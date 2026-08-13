---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식 및 형식 제공자를 사용하여 현재 객체를 문자열로 변환합니다.
type: docs
weight: 443
url: /ko/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String&, const SharedPtr<IFormatProvider>&) const 메서드

지정된 형식 및 형식 제공자를 사용하여 현재 객체를 문자열로 변환합니다.

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 형식 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |

### 반환 값

[String](../../string/) 현재 [DateTimeOffset](../) 객체의 표현.

## DateTimeOffset::ToString(const SharedPtr<IFormatProvider>&) const 메서드

지정된 형식 제공자를 사용하여 현재 객체를 문자열로 변환합니다.

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |

### 반환 값

[String](../../string/) 현재 [DateTimeOffset](../) 객체의 표현.

## DateTimeOffset::ToString(const String&) const 메서드

지정된 형식을 사용하여 현재 객체를 문자열로 변환합니다.

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 형식 문자열. |

### 반환 값

[String](../../string/) 현재 [DateTimeOffset](../) 객체의 표현.

## DateTimeOffset::ToString() const 메서드

현재 객체를 문자열로 변환합니다.

```cpp
String System::DateTimeOffset::ToString() const
```

### 반환 값

[String](../../string/) 현재 [DateTimeOffset](../) 객체의 표현.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [DateTimeOffset](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)