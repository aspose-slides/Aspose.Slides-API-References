---
title: ReplaceSelf()
second_title: Aspose.Slides for C++ API 參考
description: 將目前節點取代為指定字串的內容。
type: docs
weight: 950
url: /zh-hant/system.xml.xpath/xpathnavigator/replaceself/
---
## XPathNavigator::ReplaceSelf(String) 方法

將目前節點取代為指定字串的內容。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(String newNode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newNode | [String](../../../system/string/) | 新節點的 XML 資料字串。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XmlReader\>) 方法

將目前節點以指定的 [XmlReader](../../../system.xml/xmlreader/) 物件內容取代。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XmlReader> newNode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 定位於新節點 XML 資料的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XPathNavigator\>) 方法

將目前節點以指定的 [XPathNavigator](../) 物件內容取代。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XPathNavigator> newNode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 定位於新節點的 [XPathNavigator](../) 物件。 |

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)