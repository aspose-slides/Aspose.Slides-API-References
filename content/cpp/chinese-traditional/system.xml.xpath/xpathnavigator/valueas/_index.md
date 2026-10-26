---
title: ValueAs()
second_title: Aspose.Slides for C++ API 參考
description: 傳回目前節點的值，以指定的 Type 表示，使用指定的 IXmlNamespaceResolver 物件來解析名稱空間前置詞。
type: docs
weight: 378
url: /zh-hant/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

返回目前節點的值，以指定的 Type 表示，使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件來解析名稱空間前置詞。

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返回目前節點值的 Type。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 用於解析名稱空間前置詞的物件。 |

### 回傳值

目前節點的值，以所請求的 Type 表示。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)