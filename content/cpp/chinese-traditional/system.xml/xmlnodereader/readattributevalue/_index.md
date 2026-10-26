---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 參考
description: 將屬性值解析為一個或多個 Text、EntityReference 或 EndEntity 節點。
type: docs
weight: 430
url: /zh-hant/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() 方法

將屬性值解析為一個或多個 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### 返回值

**true** 如果有節點可返回。**false** 如果在首次呼叫時閱讀器未定位於屬性節點，或所有屬性值已被讀取。空屬性，例如 **misc=\"\"**，會返回 **true**，且僅有一個值為 [String::Empty](../../../system/string/empty/) 的節點。

## 另請參閱

* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)