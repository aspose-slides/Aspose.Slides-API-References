---
title: ReadChars()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將元素的文字內容讀入字元緩衝區。此方法設計用於透過連續呼叫來讀取大型的嵌入式文字串流。
type: docs
weight: 755
url: /zh-hant/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


將元素的文字內容讀入字元緩衝區。此方法設計用於透過連續呼叫來讀取大型的嵌入式文字串流。

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 用於作為寫入文字內容之緩衝區的字元陣列。 |
| index | **int32_t** | **buffer** 中方法可以開始寫入文字內容的位置。 |
| count | **int32_t** | 寫入 **buffer** 的字元數量。 |

### 返回值

讀取的字元數量。若讀取器未定位於元素上或在當前情境中沒有更多文字內容可返回，則可能為 0。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)