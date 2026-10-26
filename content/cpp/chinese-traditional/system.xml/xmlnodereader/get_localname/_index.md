---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 參考
description: 返回目前節點的本地名稱。
type: docs
weight: 27
url: /zh-hant/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() 方法

返回目前節點的本地名稱。

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### 返回值

此方法返回已移除前綴的目前節點名稱。舉例來說，**LocalName** 在元素 **<bk:book>** 中為 **book**。對於沒有名稱的節點類型（例如 **[Text](../../../system.text/)**、**Comment** 等），此方法返回 [String::Empty](../../../system/string/empty/)。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)