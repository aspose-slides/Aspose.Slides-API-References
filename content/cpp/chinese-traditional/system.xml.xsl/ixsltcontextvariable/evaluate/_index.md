---
title: Evaluate()
second_title: Aspose.Slides for C++ API 參考
description: 於執行時評估變數，並返回一個表示變數值的物件。
type: docs
weight: 40
url: /zh-hant/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) 方法

於執行時評估變數，並返回一個表示變數值的物件。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 表示變數執行環境的 [XsltContext](../../xsltcontext/)。 |

### 回傳值

表示變數值的 [Object](../../../system/object/)。可能的回傳類型包括 number、string、[Boolean](../../../system/boolean/)、document fragment 或 node set。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [XsltContext](../../xsltcontext/)
* 類別 [IXsltContextVariable](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)