---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，會評估是否在給定的情境中保留空白節點或將其去除。
type: docs
weight: 40
url: /zh-hant/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

當在衍生類別中覆寫時，評估是否在給定的情境中保留空白節點或將其去除。

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 目前情境中需要保留或去除的空白節點。 |

### 傳回值

**true** 表示空白應被保留；**false** 表示空白應被去除。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)