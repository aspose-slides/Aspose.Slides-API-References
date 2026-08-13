---
title: GetEncoding()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이름으로 인코딩을 가져옵니다.
type: docs
weight: 508
url: /ko/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) 메서드

이름으로 인코딩을 가져옵니다.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 이름. |

### 반환값

[Encoding](../) 지정된 이름의.

## Encoding::GetEncoding(int) 메서드

코드 페이지로 인코딩을 가져옵니다.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| codepage | int | 코드 페이지 번호. |

### 반환값

[Encoding](../) 지정된 코드 페이지의.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) 메서드

코드 페이지로 인코딩을 가져옵니다.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| codepage | int | 코드 페이지 번호. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 인코딩에 사용할 폴백. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 디코딩에 사용할 폴백. |

### 반환값

[Encoding](../) 지정된 코드 페이지의.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) 메서드

이름으로 인코딩을 가져옵니다.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 이름. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 인코딩에 사용할 폴백. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 디코딩에 사용할 폴백. |

### 반환값

[Encoding](../) 지정된 이름의.

## 참고

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Encoding](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)