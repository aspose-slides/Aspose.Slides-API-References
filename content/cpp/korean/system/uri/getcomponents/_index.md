---
title: GetComponents()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 이스케이프 방식을 사용하여 현재 객체가 나타내는 URI의 지정된 구성 요소를 반환합니다.
type: docs
weight: 378
url: /ko/system/uri/getcomponents/
---
## Uri::GetComponents(UriComponents, UriFormat) const 메서드

Returns the specified components of the URI represented by the current object using the specified escaping.

```cpp
String System::Uri::GetComponents(UriComponents components, UriFormat format) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| components | [UriComponents](../../uricomponents/) | UriComponents 값들의 비트 연산 조합으로, 반환할 URI의 부분을 지정합니다 |
| format | [UriFormat](../../uriformat/) | 특수 문자를 어떻게 이스케이프할지 지정합니다 |

### 반환값

요청된 구성 요소

## 참고

* 열거형 [UriComponents](../../uricomponents/)
* 열거형 [UriFormat](../../uriformat/)
* 클래스 [String](../../string/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)