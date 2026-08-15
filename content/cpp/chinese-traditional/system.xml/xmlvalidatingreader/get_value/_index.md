---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考
description: 傳回目前節點的文字值。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() 方法


傳回目前節點的文字值。

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### 傳回值

傳回的值取決於該節點的 XmlValidatingReader::NodeType。

## 備註



以下表格列出具有可傳回值的節點類型。所有其他節點類型傳回 [String::Empty](../../../system/string/empty/)。 

| 節點類型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的值。 |
| CDATA| CDATA 區段的內容。 |
| Comment| 註解的內容。 |
| DocumentType| 內部子集。 |
| ProcessingInstruction| 完整內容（不含目標）。 |
| SignificantWhitespace| 混合內容模型中標記之間的空白。 |
| [Text](../../../system.text/)| 文字節點的內容。 |
| Whitespace| 標記之間的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣告的內容。 |


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)