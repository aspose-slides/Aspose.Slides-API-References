---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，將屬性值剖析為一個或多個 Text、EntityReference 或 EndEntity 節點。
type: docs
weight: 677
url: /zh-hant/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() 方法

當在衍生類別中被覆寫時，會將屬性值剖析為一個或多個 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### 返回值

**true** 如果有節點可返回。**false** 如果在首次呼叫時讀取器未定位於屬性節點，或所有屬性值已被讀取。空的屬性，例如 **misc=\"\"**，會返回 **true**，並且僅有一個節點，其值為 [String::Empty](../../../system/string/empty/)。

## 另請參考

* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)