---
title: AppendChild()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個 XmlWriter 物件，用於在目前節點的子節點清單末端建立一個或多個新子節點。
type: docs
weight: 885
url: /zh-hant/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() 方法

傳回一個 [XmlWriter](../../../system.xml/xmlwriter/) 物件，用於在目前節點的子節點清單末端建立一個或多個新子節點。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### 返回值

一個 [XmlWriter](../../../system.xml/xmlwriter/) 物件，用於在目前節點的子節點清單末端建立新子節點。

## XPathNavigator::AppendChild(String) 方法

使用指定的 XML 資料字串，在目前節點的子節點清單末端建立一個新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 新子節點的 XML 資料字串。 |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 物件的 XML 內容，在目前節點的子節點清單末端建立一個新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一個定位於新子節點 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 中的節點，在目前節點的子節點清單末端建立一個新子節點。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一個定位於要新增為新子節點之節點的 [XPathNavigator](../) 物件。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlWriter](../../../system.xml/xmlwriter/)
* 類別 [XPathNavigator](../)
* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)