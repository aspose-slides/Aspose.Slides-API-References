---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，會解析變數參照並回傳代表該變數的 IXsltContextVariable。
type: docs
weight: 14
url: /zh-hant/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) 方法

當在衍生類別中被覆寫時，會解析變數參照並回傳代表該變數的 [IXsltContextVariable](../../ixsltcontextvariable/)。

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 變數在 [XPath](../../../system.xml.xpath/) 表達式中出現的前置詞。 |
| name | [String](../../../system/string/) | 變數的名稱。 |

### 回傳值

在執行時期代表變數的 [IXsltContextVariable](../../ixsltcontextvariable/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IXsltContextVariable](../../ixsltcontextvariable/)
* 類別 [String](../../../system/string/)
* 類別 [XsltContext](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)