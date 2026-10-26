---
title: ReadToNextSibling()
second_title: Aspose.Slides for C++ API 參考
description: 將 XmlReader 前進到具有指定限定名稱的下一個同層元素。
type: docs
weight: 924
url: /zh-hant/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) 方法

將 [XmlReader](../) 前進到具有指定限定名稱的下一個同層元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要移動到的同層元素的限定名稱。 |

### 返回值

**true** 如果找到匹配的同層元素；否則 **false**。如果未找到匹配的同層元素，[XmlReader](../) 會定位在父元素的結尾標籤 ([XmlReader::get_NodeType](../get_nodetype/) 值為 [XmlNodeType::EndElement](../../xmlnodetype/)) 上。

## XmlReader::ReadToNextSibling(String, String) 方法

將 [XmlReader](../) 前進到具有指定本地名稱和命名空間 URI 的下一個同層元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移動到的同層元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要移動到的同層元素的命名空間 URI。 |

### 返回值

**true** 如果找到匹配的同層元素；否則 **false**。如果未找到匹配的同層元素，[XmlReader](../) 會定位在父元素的結尾標籤 ([XmlReader::get_NodeType](../get_nodetype/) 值為 [XmlNodeType::EndElement](../../xmlnodetype/)) 上。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)