---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 소수점 숫자의 문자열 표현을 Decimal 클래스의 동등한 인스턴스로 변환합니다.
type: docs
weight: 469
url: /ko/system/decimal/parse/
---
## Decimal::Parse(const String\&) 메서드


문자열 형태의 10진수 숫자를 [Decimal](../) 클래스의 동등한 인스턴스로 변환합니다.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 숫자의 문자열 표현 |

### Return Value

지정된 문자열이 나타내는 값과 동등한 값을 나타내는 [Decimal](../) 클래스의 새 인스턴스입니다.

## Decimal::Parse(const String\&, Globalization::NumberStyles) 메서드


지정된 스타일을 사용하여 문자열 형태의 10진수 숫자를 [Decimal](../) 클래스의 동등한 인스턴스로 변환합니다.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 10진수 값의 문자열 표현 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 열거형 값들의 비트별 조합으로, **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소, 혹은 **s**를 [Decimal](../) 객체로 변환하는 과정에 대한 정보를 제공합니다. |

### Return Value

지정된 문자열이 나타내는 값과 동등한 값을 나타내는 [Decimal](../) 클래스의 새 인스턴스입니다.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드


지정된 형식 제공자를 사용하여 문자열 형태의 10진수 숫자를 [Decimal](../) 클래스의 동등한 인스턴스로 변환합니다.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 10진수 값의 문자열 표현 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자 |

### Return Value

지정된 문자열이 나타내는 값과 동등한 값을 나타내는 [Decimal](../) 클래스의 새 인스턴스입니다.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드


지정된 스타일 및 형식 제공자를 사용하여 문자열 형태의 10진수 숫자를 [Decimal](../) 클래스의 동등한 인스턴스로 변환합니다.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 10진수 값의 문자열 표현 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 열거형 값들의 비트별 조합으로, **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소, 혹은 **s**를 [Decimal](../) 객체로 변환하는 과정에 대한 정보를 제공합니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자 |

### Return Value

지정된 문자열이 나타내는 값과 동등한 값을 나타내는 [Decimal](../) 클래스의 새 인스턴스입니다.

## 또 보기

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)