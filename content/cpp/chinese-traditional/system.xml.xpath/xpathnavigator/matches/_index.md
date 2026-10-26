---
title: Matches()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷目前節點是否匹配指定的 XPathExpression。
type: docs
weight: 820
url: /zh-hant/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) 方法


判斷目前節點是否符合指定的 [XPathExpression](../../xpathexpression/)。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 包含已編譯的 [XPath](../../) 表達式的 [XPathExpression](../../xpathexpression/) 物件。 |

### 回傳值

**true** 如果目前節點符合 [XPathExpression](../../xpathexpression/)，則回傳 **true**；否則回傳 **false**。

## XPathNavigator::Matches(String) 方法


判斷目前節點是否符合指定的 [XPath](../../) 表達式。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 此 [XPath](../../) 表達式。 |

### 回傳值

**true** 如果目前節點符合指定的 [XPath](../../) 表達式，則回傳 **true**；否則回傳 **false**。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)