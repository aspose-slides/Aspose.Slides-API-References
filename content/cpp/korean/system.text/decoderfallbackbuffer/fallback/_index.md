---
title: Fallback()
second_title: Aspose.Slides for C++ API 참조
description: 실제 폴백 절차를 구현합니다.
type: docs
weight: 14
url: /ko/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 메서드

Implements actual fallback procedure.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 디코더가 디코딩에 실패한 바이트를 포함하는 바이트. |
| index | int | [Index](../../../system/index/) 오류를 일으킨 바이트. |

### 반환값

버퍼가 알 수 없는 바이트를 처리하면 true, 무시하면 false.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [DecoderFallbackBuffer](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)