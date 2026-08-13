---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.
type: docs
weight: 40
url: /ko/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 메서드

버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |
| index | int | [Buffer](../../../system/buffer/) 오프셋. |
| count | int | 디코딩할 바이트 수. |

### 반환 값

버퍼를 디코딩하는 데 필요한 문자 수.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) 메서드

버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |
| index | int | [Buffer](../../../system/buffer/) 오프셋. |
| count | int | 디코딩할 바이트 수. |
| flush | **bool** | true인 경우, 계산 후 내부 디코더 상태를 정리합니다. |

### 반환 값

버퍼를 디코딩하는 데 필요한 문자 수.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) 메서드

버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코딩할 바이트. |
| count | int | 디코딩할 바이트 수. |
| flush | **bool** | true인 경우, 계산 후 내부 디코더 상태를 정리합니다. |

### 반환 값

버퍼를 디코딩하는 데 필요한 문자 수.

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUDecoder](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)