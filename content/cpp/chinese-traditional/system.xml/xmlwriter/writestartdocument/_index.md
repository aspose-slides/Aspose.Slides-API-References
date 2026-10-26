---
title: WriteStartDocument()
second_title: Aspose.Slides C++ API 參考
description: 當在衍生類別中被覆寫時，寫入版本為 \"1.0\" 的 XML 宣告。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlwriter/writestartdocument/
---
## XmlWriter::WriteStartDocument() 方法

當在衍生類別中被覆寫時，寫入版本為 "1.0" 的 XML 宣告。

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument()=0
```

## XmlWriter::WriteStartDocument(bool) 方法

當在衍生類別中被覆寫時，寫入版本為 "1.0" 且包含 standalone 屬性的 XML 宣告。

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument(bool standalone)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| standalone | **bool** | 如果 **true**，則寫入 "standalone=yes"；如果 **false**，則寫入 "standalone=no"。 |

## 參見

* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)