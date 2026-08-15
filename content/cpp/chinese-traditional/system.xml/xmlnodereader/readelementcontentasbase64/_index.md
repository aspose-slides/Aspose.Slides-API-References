---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 參考
description: 讀取元素並解碼 Base64 內容。
type: docs
weight: 469
url: /zh-hant/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


讀取元素並解碼 Base64 內容。

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要將結果文字複製到的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中開始複製結果的偏移量。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 回傳值

寫入緩衝區的位元組數。

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)