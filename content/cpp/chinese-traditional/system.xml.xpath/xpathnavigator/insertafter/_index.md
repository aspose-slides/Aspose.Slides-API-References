---
title: InsertAfter()
second_title: Aspose.Slides C++ API 參考
description: 傳回一個 XmlWriter 物件，用於在目前所選節點之後建立新的同層節點。
type: docs
weight: 898
url: /zh-hant/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() 方法

傳回一個 [XmlWriter](../../../system.xml/xmlwriter/) 物件，用於在目前所選節點之後建立新同層節點。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### 傳回值

一個 [XmlWriter](../../../system.xml/xmlwriter/) 物件，用於在目前所選節點之後建立新同層節點。

## XPathNavigator::InsertAfter(String) 方法

使用指定的 XML 字串，於目前所選節點之後建立新同層節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新同層節點的 XML 資料字串。 |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 物件之 XML 內容，於目前所選節點之後建立新同層節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一個定位於新同層節點之 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 物件中的節點，於目前所選節點之後建立新同層節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一個定位於欲作為新同層節點之節點的 [XPathNavigator](../) 物件。 |

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlWriter](../../../system.xml/xmlwriter/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::XPath](../../)
* 程式庫 [Aspose.Slides](../../../)