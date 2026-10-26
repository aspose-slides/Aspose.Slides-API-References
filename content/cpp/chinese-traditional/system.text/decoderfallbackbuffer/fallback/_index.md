---
title: Fallback()
second_title: Aspose.Slides for C++ API 參考
description: 實作實際的回退程序。
type: docs
weight: 14
url: /zh-hant/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) 方法


實作實際的回退程序。

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) 的位元組，包括解碼器無法解碼的那一個。 |
| index | int | [Index](../../../system/index/) 的位元組，觸發錯誤。 |

### 返回值

如果緩衝區處理未知位元組則為 True，若忽略則為 false。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [DecoderFallbackBuffer](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)