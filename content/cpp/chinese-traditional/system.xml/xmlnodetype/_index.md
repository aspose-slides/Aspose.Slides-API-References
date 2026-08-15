---
title: XmlNodeType
second_title: Aspose.Slides for C++ API 參考文件
description: 指定節點的類型。
type: docs
weight: 833
url: /zh-hant/system.xml/xmlnodetype/
---
## XmlNodeType 列舉

指定節點的類型。

```cpp
enum class XmlNodeType
```

### Values

| 名稱 | 數值 | 說明 |
| --- | --- | --- |
| None | 0 | 如果尚未呼叫 **Read** 方法，[XmlReader](../xmlreader/) 會傳回此值。 |
| Element | 1 | 一個元素（例如，**<item>**）。 |
| Attribute | 2 | 屬性（例如，**id='123'**）。 |
| Text | 3 | 節點的文字內容。[XmlNodeType::Text](./) 節點不能有任何子節點。它可以作為 [XmlNodeType::Attribute](./)、[XmlNodeType::DocumentFragment](./)、[XmlNodeType::Element](./) 和 [XmlNodeType::EntityReference](./) 節點的子節點出現。 |
| CDATA | 4 | CDATA 區段（例如，**my escaped text**）。 |
| EntityReference | 5 | 實體參照（例如，**&num;**）。 |
| Entity | 6 | 實體宣告（例如，**<!ENTITY...>**）。 |
| ProcessingInstruction | 7 | 處理指示（例如，**<?pi test?>**）。 |
| Comment | 8 | 註解（例如，****）。 |
| Document | 9 | 文件物件，作為文件樹的根節點，提供對整個 XML 文件的存取。 |
| DocumentType | 10 | 文件類型宣告，由以下標記表示（例如，**<!DOCTYPE...>**）。 |
| DocumentFragment | 11 | 文件碎片。 |
| Notation | 12 | 文件類型宣告中的符號（例如，**<!NOTATION...>**）。 |
| Whitespace | 13 | 標記之間的空白。 |
| SignificantWhitespace | 14 | 混合內容模型中標記之間的空白，或 **xml:space=\"preserve\"** 範圍內的空白。 |
| EndElement | 15 | 結束元素標籤（例如，****）。 |
| EndEntity | 16 | 當 [XmlReader](../xmlreader/) 因呼叫 [XmlReader::ResolveEntity](../xmlreader/resolveentity/) 而達到實體取代的結尾時傳回。 |
| XmlDeclaration | 17 | XML 宣告（例如，**<?xml version='1.0'?>**）。[XmlNodeType::XmlDeclaration](./) 節點必須是文件中的第一個節點。它不能有子節點。它是 [XmlNodeType::Document](./) 節點的子節點。它可以有提供版本與編碼資訊的屬性。 |

## 參見

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)