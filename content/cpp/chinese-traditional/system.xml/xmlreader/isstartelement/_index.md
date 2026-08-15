---
title: IsStartElement()
second_title: Aspose.Slides for C++ API 參考
description: "呼叫 XmlReader::MoveToContent 並測試目前的內容節點是否為開始標記或空元素標記。"
type: docs
weight: 885
url: /zh-hant/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() 方法


呼叫 [XmlReader::MoveToContent](../movetocontent/) 並測試目前的內容節點是否為開始標記或空元素標記。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### 回傳值

**true** 若 [XmlReader::MoveToContent](../movetocontent/) 找到開始標記或空元素標記；**false** 若找到的節點類型不是 [XmlNodeType::Element](../../xmlnodetype/)。

## XmlReader::IsStartElement(String) 方法


呼叫 [XmlReader::MoveToContent](../movetocontent/) 並測試目前的內容節點是否為開始標記或空元素標記，以及找到的元素之 [XmlReader::get_Name](../get_name/) 值是否與給定的參數相符。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 與找到的元素之 **Name** 值相匹配的字串。 |

### 回傳值

**true** 若結果節點為元素且 **Name** 值與指定的字串相匹配。**false** 若找到的節點類型不是 [XmlNodeType::Element](../../xmlnodetype/)，或元素的 **Name** 值未與指定的字串匹配。

## XmlReader::IsStartElement(String, String) 方法


呼叫 [XmlReader::MoveToContent](../movetocontent/) 並測試目前的內容節點是否為開始標記或空元素標記，以及找到的元素之 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值是否與給定的字串相符。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 與找到的元素之 **LocalName** 值相匹配的字串。 |
| ns | [String](../../../system/string/) | 與找到的元素之 **NamespaceURI** 值相匹配的字串。 |

### 回傳值

**true** 若結果節點為元素。**false** 若找到的節點類型不是 [XmlNodeType::Element](../../xmlnodetype/)，或元素的 **LocalName** 與 **NamespaceURI** 值未與指定的字串匹配。

## 另請參閱

* 類別 [XmlReader](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)