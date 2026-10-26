---
title: Fallback()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 디코딩 실패를 처리합니다.
type: docs
weight: 27
url: /ko/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 메서드

디코딩 실패를 처리합니다.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 알 수 없는 바이트; 무시됨. |
| index | int | 알 수 없는 바이트 오프셋; 무시됨. |

### 반환 값

대체 문자열이 제공되고 비어 있지 않으면 true, 그렇지 않으면 false.

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [DecoderReplacementFallbackBuffer](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)