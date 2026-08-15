---
title: ReadBinHex()
second_title: Aspose.Slides for C++ API 參考
description: 解碼 BinHex 並返回已解碼的二進位位元組。
type: docs
weight: 781
url: /zh-hant/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


解碼 **BinHex** 並返回已解碼的二進位位元組。

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 作為緩衝區的位元組陣列，解碼後的二進位位元組將寫入此緩衝區。 |
| offset | **int32_t** | 陣列中以零為基礎的索引，指示方法可開始寫入緩衝區的位置。 |
| len | **int32_t** | 要寫入緩衝區的位元組數。 |

### 返回值

寫入緩衝區的位元組數。

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)