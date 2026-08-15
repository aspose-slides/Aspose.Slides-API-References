---
title: Fallback()
second_title: Aspose.Slides C++ API 參考文件
description: 處理解碼失敗。
type: docs
weight: 27
url: /zh-hant/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method


處理解碼失敗。

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/)的未知位元組；已忽略。 |
| index | int | 未知位元組的偏移量；已忽略。 |

### 返回值

True if replacement string is provided and is not empty, false otherwise.

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [DecoderReplacementFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 程式庫 [Aspose.Slides](../../../)