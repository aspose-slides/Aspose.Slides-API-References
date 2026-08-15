---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API 參考
description: 讀取元素並解碼 BinHex 內容。
type: docs
weight: 677
url: /zh-hant/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取元素並解碼 **BinHex** 內容。

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要將結果文字複製到的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 緩衝區中的位移，指示從何處開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 回傳值

寫入緩衝區的位元組數。

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)