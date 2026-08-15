---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 參考文件
description: 在衍生類別中覆寫時，取得目前節點的本地名稱。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() method

在衍生類別中覆寫時，取得目前節點的本地名稱。

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### 回傳值

移除前置詞後的目前節點名稱。例如，**LocalName** 為 **book**，對於元素 **<bk:book>**。對於沒有名稱的節點類型（例如 **[Text](../../../system.text/)**、**Comment** 等），此方法會回傳 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)