---
title: Convert()
second_title: Aspose.Slides for C++ API 참조
description: 바이트를 문자로 변환합니다.
type: docs
weight: 79
url: /ko/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) 메서드

바이트를 문자로 변환합니다.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코드할 바이트. |
| byteIndex | int | 입력 버퍼 오프셋. |
| byteCount | int | 입력 버퍼 크기. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 대상 문자 버퍼. |
| charIndex | int | 대상 배열 오프셋. |
| charCount | int | 대상 배열 크기. |
| flush | **bool** | true이면 계산 후 내부 디코더 상태를 정리합니다. |
| bytesUsed | int\& | 읽은 바이트 수를 저장할 변수에 대한 참조. |
| charsUsed | int\& | 작성된 문자 수를 저장할 변수에 대한 참조. |
| completed | **bool**\& | 입력 버퍼가 소진되면 true, 그렇지 않으면 false로 설정할 변수에 대한 참조. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) 메서드

바이트를 문자로 변환합니다.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코드할 바이트. |
| byteCount | int | 입력 버퍼 크기. |
| chars | char_t * | 대상 문자 버퍼. |
| charCount | int | 대상 배열 크기. |
| flush | **bool** | true이면 계산 후 내부 디코더 상태를 정리합니다. |
| bytesUsed | int\& | 읽은 바이트 수를 저장할 변수에 대한 참조. |
| charsUsed | int\& | 작성된 문자 수를 저장할 변수에 대한 참조. |
| completed | **bool**\& | 입력 버퍼가 소진되면 true, 그렇지 않으면 false로 설정할 변수에 대한 참조. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Decoder](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)