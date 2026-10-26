---
title: GetChars()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼를 디코딩한 결과로 얻어지는 문자를 가져옵니다.
type: docs
weight: 53
url: /ko/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 메서드

디코딩된 버퍼에서 결과로 나오는 문자를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |
| byteIndex | int | 입력 버퍼 오프셋. |
| byteCount | int | 입력 버퍼 크기. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 목적지 문자 버퍼. |
| charIndex | int | 목적지 배열 오프셋. |

### 반환값

작성된 문자 수.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) 메서드

디코딩된 버퍼에서 결과로 나오는 문자를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |
| byteIndex | int | 입력 버퍼 오프셋. |
| byteCount | int | 입력 버퍼 크기. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 목적지 문자 버퍼. |
| charIndex | int | 목적지 배열 오프셋. |
| flush | **bool** | true이면 계산 후 내부 디코더 상태를 정리합니다. |

### 반환값

작성된 문자 수.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) 메서드

디코딩된 버퍼에서 결과로 나오는 문자를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코딩할 바이트. |
| byteCount | int | 입력 버퍼 크기. |
| chars | char_t * | 목적지 문자 버퍼. |
| charCount | int | 목적지 배열 크기. |
| flush | **bool** | true이면 계산 후 내부 디코더 상태를 정리합니다. |

### 반환값

작성된 문자 수.

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUDecoder](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)