---
title: Convert()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 문자를 바이트로 변환합니다.
type: docs
weight: 79
url: /ko/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

문자를 바이트로 변환합니다.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자. |
| charIndex | int | 입력 버퍼 오프셋. |
| charCount | int | 입력 버퍼 크기. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 목적지 바이트 버퍼. |
| byteIndex | int | 목적지 배열 오프셋. |
| byteCount | int | 목적지 배열 크기. |
| flush | **bool** | true인 경우, 계산 후 내부 인코더 상태를 정리합니다. |
| charsUsed | int\& | 읽은 문자 수를 저장할 변수에 대한 참조. |
| bytesUsed | int\& | 작성된 바이트 수를 저장할 변수에 대한 참조. |
| completed | **bool**\& | 입력 버퍼가 소진되면 true, 그렇지 않으면 false가 설정되는 변수에 대한 참조. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

문자를 바이트로 변환합니다.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자. |
| charCount | int | 입력 버퍼 크기. |
| bytes | **uint8_t** * | 목적지 바이트 버퍼. |
| byteCount | int | 목적지 배열 크기. |
| flush | **bool** | true인 경우, 계산 후 내부 인코더 상태를 정리합니다. |
| charsUsed | int\& | 읽은 문자 수를 저장할 변수에 대한 참조. |
| bytesUsed | int\& | 작성된 바이트 수를 저장할 변수에 대한 참조. |
| completed | **bool**\& | 입력 버퍼가 소진되면 true, 그렇지 않으면 false가 설정되는 변수에 대한 참조. |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Encoder](../)
* 네임스페이스 [System::Text](../../)
* Library [Aspose.Slides](../../../)