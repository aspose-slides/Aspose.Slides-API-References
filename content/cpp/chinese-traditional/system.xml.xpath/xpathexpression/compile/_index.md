---
title: Compile()
second_title: Aspose.Slides for C++ API 參考文件
description: 編譯指定的 XPath 表達式，並返回一個代表該 XPath 表達式的 XPathExpression 物件。
type: docs
weight: 66
url: /zh-hant/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method

編譯指定的 [XPath](../../) 表達式，並返回一個代表 [XPath](../../) 表達式的 [XPathExpression](../) 物件。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 一個 [XPath](../../) 表達式。 |

### Return Value

一個 [XPathExpression](../) 物件。

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method

編譯指定的 [XPath](../../) 表達式，使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件進行命名空間解析，並返回一個代表 [XPath](../../) 表達式的 [XPathExpression](../) 物件。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 一個 [XPath](../../) 表達式。 |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 一個實作 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 介面的物件，用於命名空間解析。 |

### Return Value

一個 [XPathExpression](../) 物件。

## See Also

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XPathExpression](../)
* 類別 [String](../../../system/string/)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空間 [System::Xml::XPath](../../)
* 程式庫 [Aspose.Slides](../../../)