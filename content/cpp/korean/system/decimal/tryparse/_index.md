---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 Decimal 값으로 변환합니다.
type: docs
weight: 482
url: /ko/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) 메서드

지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 [Decimal](../) 값으로 변환합니다.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| result | [Decimal](../)\& | 변환 결과가 저장되는 [Decimal](../) 변수에 대한 참조 |

### 반환 값

변환에 성공하면 true, 그렇지 않으면 false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 [Decimal](../) 값으로 변환합니다.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트 단위 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |
| result | [Decimal](../)\& | 출력 인수; 변환 결과를 포함합니다 |

### 반환 값

변환에 성공하면 true, 그렇지 않으면 false

## 또 보기

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)