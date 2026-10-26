---
title: Fallback()
second_title: Aspose.Slides for C++ API 參考
description: 處理解碼失敗。
type: docs
weight: 27
url: /zh-hant/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 方法

處理解碼失敗。

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 未知位元組; 已忽略。 |
| index | int | 未知位元組的偏移量; 已忽略。 |

### 返回值

永遠不會實際返回，而是拋出例外。

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [DecoderExceptionFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)