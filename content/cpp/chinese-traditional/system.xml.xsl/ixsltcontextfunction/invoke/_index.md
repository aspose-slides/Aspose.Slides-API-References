---
title: Invoke()
second_title: Aspose.Slides for C++ API 參考
description: 提供在給定上下文中使用給定參數呼叫函式的方法。
type: docs
weight: 53
url: /zh-hant/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

提供在給定上下文中使用給定參數呼叫函式的方法。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 函式呼叫的 XSLT 上下文。 |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 函式呼叫的參數。每個參數都是陣列中的一個元素。 |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 函式呼叫的上下文節點。 |

### 返回值

表示函式返回值的 [Object](../../../system/object/)。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [XsltContext](../../xsltcontext/)
* 類別 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 類別 [IXsltContextFunction](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)