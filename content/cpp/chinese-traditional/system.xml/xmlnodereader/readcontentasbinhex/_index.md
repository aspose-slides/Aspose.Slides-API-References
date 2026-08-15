---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API 參考
description: 讀取內容並返回已解碼的 BinHex 二進位位元組。
type: docs
weight: 456
url: /zh-hant/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

讀取內容並返回已解碼的 BinHex 二進位位元組。

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用來複製結果文字的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 緩衝區的偏移量，指定從哪裡開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數會從此方法返回。 |

### 返回值

寫入緩衝區的位元組數。

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)