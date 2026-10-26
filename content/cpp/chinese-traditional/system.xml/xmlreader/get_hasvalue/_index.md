---
title: get_HasValue()
second_title: Aspose.Slides for C++ API 參考文件
description: "當在衍生類別中被覆寫時，取得一個值，指示目前節點是否可以具有 XmlReader::get_Value 值。"
type: docs
weight: 79
url: /zh-hant/system.xml/xmlreader/get_hasvalue/
---
## XmlReader::get_HasValue() 方法

When overridden in a derived class, gets a value indicating whether the current node can have a [XmlReader::get_Value](../get_value/) value.

```cpp
virtual bool System::Xml::XmlReader::get_HasValue()
```

### 返回值

**true** 若讀取器當前所在的節點可以具有 **Value**，則返回；否則返回 **false**。如果為 **false**，則該節點的值為 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)