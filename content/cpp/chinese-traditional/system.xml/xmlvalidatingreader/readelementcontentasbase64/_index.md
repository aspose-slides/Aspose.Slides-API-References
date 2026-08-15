---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 參考
description: 讀取元素並解碼 Base64 內容。
type: docs
weight: 586
url: /zh-hant/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取元素並解碼 Base64 內容。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用於複製結果文字的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中的偏移量，指示從何處開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 傳回值

寫入緩衝區的位元組數。

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)