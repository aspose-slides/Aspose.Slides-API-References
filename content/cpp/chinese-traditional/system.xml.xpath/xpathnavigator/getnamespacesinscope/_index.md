---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回目前節點的範圍內命名空間。
type: docs
weight: 430
url: /zh-hant/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope(XmlNamespaceScope) 方法

返回目前節點的範圍內命名空間。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) | 一個 XmlNamespaceScope 值，指定要返回的命名空間。 |

### 回傳值

一個 IDictionary 集合，鍵為前綴的命名空間名稱。

## 參見

* 列舉 [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)