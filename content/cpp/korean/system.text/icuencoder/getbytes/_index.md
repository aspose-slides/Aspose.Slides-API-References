---
title: GetBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼를 인코딩한 결과 바이트를 반환합니다.
type: docs
weight: 53
url: /ko/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) 메서드

버퍼를 인코딩한 결과 바이트를 반환합니다.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자. |
| charIndex | int | 소스 배열 오프셋. |
| charCount | int | 소스 서브배열 길이. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 대상 바이트 버퍼. |
| byteIndex | int | 대상 버퍼 오프셋. |
| flush | **bool** | true이면 계산 후 내부 인코더 상태를 정리합니다. |

### 반환값

작성된 바이트 수.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) 메서드

버퍼를 인코딩한 결과 바이트를 반환합니다.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자. |
| charCount | int | 소스 배열 길이. |
| bytes | **uint8_t** * | 대상 바이트 버퍼. |
| byteCount | int | 대상 버퍼 크기. |
| flush | **bool** | true이면 계산 후 내부 인코더 상태를 정리합니다. |

### 반환값

작성된 바이트 수.

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUEncoder](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)