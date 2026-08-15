---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回目前節點的文字值。
type: docs
weight: 79
url: /zh-hant/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() method

返回目前節點的文字值。

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### 返回值

返回的值取決於節點的 [XmlTextReader::get_NodeType](../get_nodetype/) 值。

## 備註

下表列出了具有可返回值的節點類型。所有其他節點類型返回 [String::Empty](../../../system/string/empty/)。

| 節點類型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的值。 |
| CDATA| CDATA 區段的內容。 |
| Comment| 註解的內容。 |
| DocumentType| 內部子集合。 |
| ProcessingInstruction| 整個內容，排除目標。 |
| SignificantWhitespace| 位於 `xml:space='preserve'` 範圍內的空白。 |
| [Text](../../../system.text/)| 文字節點的內容。 |
| Whitespace| 標記之間的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣告的內容。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)