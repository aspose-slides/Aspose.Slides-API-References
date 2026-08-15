---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides C++ 版 API 參考
description: 讀取元素並解碼 BinHex 內容。
type: docs
weight: 612
url: /zh-hant/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取元素並解碼 BinHex 內容。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用於複製結果文字的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中開始複製結果的偏移量。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法回傳。 |

### 回傳值

寫入緩衝區的位元組數。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)