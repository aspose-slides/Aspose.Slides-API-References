---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 參考
description: 讀取元素並解碼 Base64 內容。
type: docs
weight: 768
url: /zh-hant/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取元素並解碼 **Base64** 內容。

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 緩衝區 buffer，用於複製結果文字。此值不能為 **nullptr**。 |
| index | **int32_t** | 緩衝區 buffer 的偏移量，指示從何處開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區 buffer 的最大位元組數。實際複製的位元組數由此方法回傳。 |

### 回傳值

寫入緩衝區 buffer 的位元組數。

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)