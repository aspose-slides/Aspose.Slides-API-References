---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考
description: 在衍生類別中被覆寫時，取得目前節點的文字值。
type: docs
weight: 92
url: /zh-hant/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() 方法


當在衍生類別中被覆寫時，取得目前節點的文字值。

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### 返回值

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.
## 備註



以下表格列出具有可返回值的節點類型。所有其他節點類型返回 [String::Empty](../../../system/string/empty/)。 

| 節點類型 | 值 |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 屬性的值。 |
| `CDATA`| CDATA 區段的內容。 |
| `Comment`| 註解的內容。 |
| `DocumentType`| 內部子集。 |
| `ProcessingInstruction`| 整個內容，排除目標。 |
| `SignificantWhitespace`| 混合內容模型中標記之間的空白。 |
| `[Text](../../../system.text/)`| 文字節點的內容。 |
| `Whitespace`| 標記之間的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣告的內容。 |


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)