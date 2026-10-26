---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API 參考
description: 讀取內容並返回 Base64 解碼後的二進位位元組。
type: docs
weight: 755
url: /zh-hant/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取內容並返回 Base64 解碼後的二進位位元組。

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 將結果文字複製到的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中開始複製結果的偏移量。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 返回值

寫入緩衝區的位元組數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)