---
title: PrependChild()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個用於在目前節點的子節點列表開頭建立新子節點的 XmlWriter 物件。
type: docs
weight: 872
url: /zh-hant/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() 方法

傳回一個用於在目前節點的子節點列表開頭建立新子節點的 [XmlWriter](../../../system.xml/xmlwriter/) 物件。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### 返回值

一個用於在目前節點的子節點列表開頭建立新子節點的 [XmlWriter](../../../system.xml/xmlwriter/) 物件。

## XPathNavigator::PrependChild(String) 方法

使用指定的 XML 字串，在目前節點的子節點列表開頭建立新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 新子節點的 XML 資料字串。 |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 物件的 XML 內容，在目前節點的子節點列表開頭建立新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一個定位於新子節點 XML 資料之上的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 物件中的節點，在目前節點的子節點列表開頭建立新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一個定位於要添加為新子節點之節點的 [XPathNavigator](../) 物件。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlWriter](../../../system.xml/xmlwriter/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)