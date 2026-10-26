---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 參考
description: 傳回目前節點的本地名稱。
type: docs
weight: 27
url: /zh-hant/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() 方法

傳回目前節點的本地名稱。

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```

### 返回值

目前節點去除前綴後的名稱。例如，**LocalName** 在元素 **<bk:book>** 中為 **book**。對於沒有名稱的節點類型（例如 **[Text](../../../system.text/)**、**Comment** 等），此方法傳回 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)