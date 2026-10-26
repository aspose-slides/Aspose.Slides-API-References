---
title: ReadAttributeValue()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 將屬性值剖析為一個或多個 Text、EntityReference 或 EndEntity 節點。
type: docs
weight: 508
url: /zh-hant/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() 方法

將屬性值剖析為一個或多個 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### 傳回值

**true** 若有節點可傳回。**false** 若在初始呼叫時讀取器未定位於屬性節點，或所有屬性值皆已讀取。空的屬性，例如 **misc=""**，會傳回 **true** 並帶有一個值為 [String::Empty](../../../system/string/empty/) 的單一節點。

## 另請參閱

* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)