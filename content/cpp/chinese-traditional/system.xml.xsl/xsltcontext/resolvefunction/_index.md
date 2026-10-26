---
title: ResolveFunction()
second_title: Aspose.Slides C++ API 參考
description: 當在衍生類別中被覆寫時，會解析函式參考並傳回代表該函式的 IXsltContextFunction。IXsltContextFunction 於執行時用來取得函式的返回值。
type: docs
weight: 27
url: /zh-hant/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) 方法


當在衍生類別中被覆寫時，解析函式參考並回傳代表該函式的 [IXsltContextFunction](../../ixsltcontextfunction/)。[IXsltContextFunction](../../ixsltcontextfunction/) 於執行時用來取得該函式的返回值。

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 函式的前置詞，出現在 [XPath](../../../system.xml.xpath/) 表達式中。 |
| name | [String](../../../system/string/) | 函式的名稱。 |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | 用於被解析之函式的參數型別陣列。此可讓您在具相同名稱的函式之間進行選擇（例如，重載的函式）。 |

### 返回值

代表該函式的 [IXsltContextFunction](../../ixsltcontextfunction/)。

## 另見

* 列舉 [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IXsltContextFunction](../../ixsltcontextfunction/)
* 類別 [String](../../../system/string/)
* 類別 [XsltContext](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)