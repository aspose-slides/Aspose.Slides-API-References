---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API 參考
description: 讀取內容並返回已 BinHex 解碼的二進位位元組。
type: docs
weight: 781
url: /zh-hant/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取內容並返回已 **BinHex** 解碼的二進位位元組。

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用於複製結果文字的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中開始複製結果的偏移量。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法返回。 |

### 回傳值

寫入緩衝區的位元組數。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)