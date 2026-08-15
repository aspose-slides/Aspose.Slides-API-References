---
title: ValueAs()
second_title: Aspose.Slides for C++ API 參考
description: 傳回項目的值，以指定的型別。
type: docs
weight: 131
url: /zh-hant/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) 方法


傳回項目的值，以指定的型別。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要將項目值傳回的型別。 |

### 回傳值

項目的值，以請求的型別。

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法


當在衍生類別中覆寫時，傳回項目的值，使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件解析命名空間前綴所指定的型別。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 要將項目值傳回的型別。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於解析命名空間前綴的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。 |

### 回傳值

項目的值，以請求的型別。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XPathItem](../)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)