---
title: ReadBase64()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 Base64 解碼，並返回解碼後的二進位位元組。
type: docs
weight: 768
url: /zh-hant/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

解碼 Base64 並返回解碼後的二進位位元組。

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 作為緩衝區的字元陣列，文字內容將寫入其中。 |
| offset | **int32_t** | 指定方法可以開始寫入緩衝區的陣列之零基索引。 |
| len | **int32_t** | 要寫入緩衝區的位元組數。 |

### 返回值

寫入緩衝區的位元組數。

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)