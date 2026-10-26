---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 參考
description: 讀取元素並解碼 Base64 內容。
type: docs
weight: 651
url: /zh-hant/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


讀取元素並解碼 Base64 內容。

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要將結果文字複製進去的緩衝區。此值不能是 **nullptr**。 |
| index | **int32_t** | 在緩衝區中開始複製結果的位移。 |
| count | **int32_t** | 要複製到緩衝區的最大位元組數。實際複製的位元組數由此方法回傳。 |

### 返回值

寫入緩衝區的位元組數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)