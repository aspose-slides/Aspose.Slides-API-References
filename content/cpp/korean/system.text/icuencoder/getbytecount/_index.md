---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼를 인코딩하는 데 필요한 바이트 수를 가져옵니다.
type: docs
weight: 40
url: /ko/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) 메서드

버퍼를 인코딩하는 데 필요한 바이트 수를 가져옵니다.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자. |
| index | int | [Buffer](../../../system/buffer/) 오프셋. |
| count | int | 인코딩할 문자 수. |
| flush | **bool** | true인 경우, 계산 후 내부 인코더 상태를 정리합니다. |

### 반환 값

버퍼를 인코딩하는 데 필요한 바이트 수.

## ICUEncoder::GetByteCount(const char_t *, int, bool) 메서드

버퍼를 인코딩하는 데 필요한 바이트 수를 가져옵니다.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자. |
| count | int | 인코딩할 문자 수. |
| flush | **bool** | true인 경우, 계산 후 내부 인코더 상태를 정리합니다. |

### 반환 값

버퍼를 인코딩하는 데 필요한 바이트 수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUEncoder](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)