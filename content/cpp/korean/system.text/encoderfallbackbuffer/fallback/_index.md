---
title: Fallback()
second_title: Aspose.Slides for C++ API 참조
description: 실제 폴백 절차를 구현합니다.
type: docs
weight: 14
url: /ko/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) 메서드

실제 폴백 절차를 구현합니다.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| charUnknown | char_t | 인코더가 인코딩에 실패한 문자입니다. |
| index | int | [Index](../../../system/index/) 오류를 일으킨 문자입니다. |

### 반환 값

버퍼가 알 수 없는 문자를 처리하면 true, 무시하면 false를 반환합니다.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) 메서드

실제 폴백 절차를 구현합니다.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| charUnknownHigh | char_t | 오류를 일으킨 서러게이트 쌍의 높은 부분입니다. |
| charUnknownLow | char_t | 오류를 일으킨 서러게이트 쌍의 낮은 부분입니다. |
| index | int | [Index](../../../system/index/) 오류를 일으킨 문자입니다. |

### 반환 값

버퍼가 알 수 없는 문자를 처리하면 true, 무시하면 false를 반환합니다.

## 관련 항목

* 클래스 [EncoderFallbackBuffer](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)