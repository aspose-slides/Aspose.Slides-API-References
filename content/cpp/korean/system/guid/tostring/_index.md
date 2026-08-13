---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 GUID를 문자열 표현으로 변환합니다.
type: docs
weight: 79
url: /ko/system/guid/tostring/
---
## Guid::ToString() const 메서드

현재 객체가 나타내는 GUID를 문자열 표현으로 변환합니다.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const 메서드

현재 객체가 나타내는 GUID를 지정된 문자열 형식을 사용하여 문자열 표현으로 변환합니다.

```cpp
String System::Guid::ToString(const String &format) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 사용할 형식 |

### 반환값

현재 객체가 나타내는 GUID 값의 문자열 표현

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드

현재 객체가 나타내는 GUID를 지정된 문자열 형식과 문화권을 사용하여 문자열 표현으로 변환합니다.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 사용할 형식 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 사용할 문화권 |

### 반환값

현재 객체가 나타내는 GUID 값의 문자열 표현

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Guid](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)