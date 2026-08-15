---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 參考
description: 將屬性值解析為一個或多個 Text、EntityReference 或 EndEntity 節點。
type: docs
weight: 560
url: /zh-hant/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() 方法

將屬性值解析為一個或多個 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### 返回值

如果有節點可返回，則為 **true**。如果在首次調用時讀取器未定位於屬性節點，或所有屬性值已被讀取，則為 **false**。空屬性，例如 **misc=\"\"**，會返回 **true**，並伴隨一個值為 [String::Empty](../../../system/string/empty/) 的單一節點。

## 相關參考

* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)