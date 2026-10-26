---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個用於在目前選取的節點之前建立新兄弟節點的 XmlWriter 物件。
type: docs
weight: 911
url: /zh-hant/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() 方法

傳回一個用於在目前選取的節點之前建立新兄弟節點的 [XmlWriter](../../../system.xml/xmlwriter/) 物件。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### 回傳值

一個用於在目前選取的節點之前建立新兄弟節點的 [XmlWriter](../../../system.xml/xmlwriter/) 物件。

## XPathNavigator::InsertBefore(String) 方法

使用指定的 XML 字串，在目前選取的節點之前建立新兄弟節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新兄弟節點的 XML 資料字串。 |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 物件之 XML 內容，在目前選取的節點之前建立新兄弟節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一個定位於新兄弟節點之 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 中的節點，在目前選取的節點之前建立新兄弟節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一個定位於要作為新兄弟節點之節點的 [XPathNavigator](../) 物件。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlWriter](../../../system.xml/xmlwriter/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)