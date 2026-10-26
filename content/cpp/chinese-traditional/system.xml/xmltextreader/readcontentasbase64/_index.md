---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API 參考文件
description: 讀取內容並返回 Base64 解碼的二進位位元組。
type: docs
weight: 638
url: /zh-hant/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取內容並返回 **Base64** 解碼的二進位位元組。

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 緩衝區，用於複製結果文字。此值不能為 **nullptr**。 |
| index | **int32_t** | 在緩衝區中的偏移量，指示從何處開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法回傳。 |

### 回傳值

寫入緩衝區的位元組數。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)