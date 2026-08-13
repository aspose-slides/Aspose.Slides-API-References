---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.
type: docs
weight: 14
url: /ko/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| result | **float**\& | 변환 결과가 저장되는 단정밀도 부동소수점 변수에 대한 참조. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함) 을 단정밀도 부동소수점 값으로 변환합니다.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터. |
| result | **float**\& | 변환 결과가 저장되는 단정밀도 부동소수점 변수에 대한 참조. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) 메서드

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) 메서드

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) 메서드

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## 참고

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입별명 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [Single](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)