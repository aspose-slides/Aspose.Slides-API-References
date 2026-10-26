---
title: HexUnescape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자에 대한 16진수 표현을 문자로 변환합니다.
type: docs
weight: 443
url: /ko/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) 메서드

문자에 대한 16진수 표현을 문자로 변환합니다.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | 문자에 대한 16진수 표현을 포함하는 문자열 |
| index | **int32_t**\& | **pattern**에서 문자에 대한 16진수 표현이 시작되는 위치 |

### 반환값

인덱스 **index** 위치에 있는 16진수 인코딩에 의해 표현된 문자입니다. **index** 위치의 문자가 16진수 인코딩이 아닌 경우 해당 문자가 반환됩니다. **index** 값은 반환된 문자 다음 문자를 가리키도록 증가합니다.

## 참조

* 클래스 [String](../../string/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)