---
title: Fallback()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인코딩 실패를 처리합니다.
type: docs
weight: 27
url: /ko/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) 메서드

인코딩 실패를 처리합니다.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charUnknown | char_t | 알 수 없는 문자; 무시됩니다. |
| index | int | 알 수 없는 문자 오프셋; 무시됩니다. |

### 반환값

실제로 반환되지 않고, 대신 예외가 발생합니다.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) 메서드

인코딩 실패를 처리합니다.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charUnknownHigh | char_t | 오류를 발생시킨 교체 쌍의 상위 부분. |
| charUnknownLow | char_t | 오류를 발생시킨 교체 쌍의 하위 부분. |
| index | int | 알 수 없는 문자 오프셋; 무시됩니다. |

### 반환값

실제로 반환되지 않고, 대신 예외가 발생합니다.

## 참조

* 클래스 [EncoderExceptionFallbackBuffer](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)