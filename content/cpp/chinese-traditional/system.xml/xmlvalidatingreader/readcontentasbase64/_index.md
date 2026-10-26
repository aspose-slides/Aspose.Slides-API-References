---
title: ReadContentAsBase64()
second_title: Aspose.Slides C++ API 參考
description: 讀取內容並返回 Base64 解碼後的二進位位元組。
type: docs
weight: 573
url: /zh-hant/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

讀取內容並返回 Base64 解碼後的二進位位元組。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要將結果文字複製到的緩衝區。此值不能為 **nullptr**。 |
| index | **int32_t** | 緩衝區中開始複製結果的位移。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法回傳。 |

### 回傳值

寫入緩衝區的位元組數。

## 另請參考

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)