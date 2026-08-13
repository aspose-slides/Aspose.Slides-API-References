---
title: Fallback()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인코딩 실패를 처리합니다.
type: docs
weight: 27
url: /ko/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) 메서드

인코딩 실패를 처리합니다.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charUnknown | char_t | 알 수 없는 문자; 무시됩니다. |
| index | int | 알 수 없는 문자 위치; 무시됩니다. |

### 반환 값

대체 문자열이 제공되고 비어 있지 않으면 true, 그렇지 않으면 false.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) 메서드

인코딩 실패를 처리합니다.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charUnknownHigh | char_t | 오류를 일으킨 서러게이트 쌍의 상위 부분. |
| charUnknownLow | char_t | 오류를 일으킨 서러게이트 쌍의 하위 부분. |
| index | int | 알 수 없는 문자 위치; 무시됩니다. |

### 반환 값

대체 문자열이 제공되고 비어 있지 않으면 true, 그렇지 않으면 false.

## 참고

* 클래스 [EncoderReplacementFallbackBuffer](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)