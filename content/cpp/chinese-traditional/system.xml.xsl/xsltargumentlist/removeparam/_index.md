---
title: RemoveParam()
second_title: Aspose.Slides for C++ API 參考
description: 從 XsltArgumentList 中移除參數。
type: docs
weight: 66
url: /zh-hant/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) 方法

從 [XsltArgumentList](../) 中移除參數。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 要移除的參數名稱。[XsltArgumentList](../) 不會檢查傳入的名稱是否為有效的本地名稱；但是，名稱不能為 **nullptr**。 |
| namespaceUri | const [String](../../../system/string/)\& | 要移除的參數的命名空間 URI。 |

### 傳回值

參數物件，若未找到則為 **nullptr**。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [String](../../../system/string/)
* 類別 [XsltArgumentList](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)