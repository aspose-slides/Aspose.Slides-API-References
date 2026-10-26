---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API 參考
description: 讀取內容並返回已 BinHex 解碼的二進位位元組。
type: docs
weight: 664
url: /zh-hant/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法


讀取內容並返回已 **BinHex** 解碼的二進位位元組。

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 將結果文字複製到的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 緩衝區中開始複製結果的偏移量。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 傳回值

寫入緩衝區的位元組數。

## 相關資訊

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)