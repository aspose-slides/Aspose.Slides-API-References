---
title: Convert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 인코딩 간에 바이트를 변환합니다.
type: docs
weight: 378
url: /ko/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) 메서드

두 인코딩 간에 바이트를 변환합니다.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 원본 인코딩. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 대상 인코딩. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 변환할 바이트. |

### 반환값

변환된 바이트.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) 메서드

두 인코딩 간에 바이트를 변환합니다.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 원본 인코딩. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 대상 인코딩. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 변환할 바이트. |
| index | int | 슬라이스 시작 위치. |
| count | int | 슬라이스 크기. |

### 반환값

변환된 바이트.

## 관련 항목

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [EncodingPtr](../../../system/encodingptr/)
* 클래스 [Encoding](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)