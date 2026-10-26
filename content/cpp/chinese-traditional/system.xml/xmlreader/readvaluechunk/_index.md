---
title: ReadValueChunk()
second_title: Aspose.Slides for C++ API 參考
description: 讀取嵌入於 XML 文件中的大型文字流。
type: docs
weight: 807
url: /zh-hant/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法


讀取嵌入於 XML 文件中的大型文字流。

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 用於作為寫入文字內容的緩衝區的字符陣列。此值不可為 **nullptr**。 |
| index | **int32_t** | 緩衝區內的偏移位置，[XmlReader](../) 可以從此處開始複製結果。 |
| count | **int32_t** | 要複製到緩衝區的最大字符數量。實際複製的字符數量由此方法返回。 |

### 返回值

讀入緩衝區的字符數量。當沒有更多文字內容時，返回值為零。

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)