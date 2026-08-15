---
title: ValueAs()
second_title: Aspose.Slides for C++ API 參考文件
description: 以指定用於解析命名空間前綴的 IXmlNamespaceResolver 物件，傳回已驗證的 XML 元素或屬性的值，且型別符合所指定的類型。
type: docs
weight: 144
url: /zh-hant/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


傳回已驗證的 XML 元素或屬性的值，該值以使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件（用於解析命名空間前綴）所指定的型別表示。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要將已驗證的 XML 元素或屬性的值轉換為的型別。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於解析命名空間前綴的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。 |

### 回傳值

已驗證的 XML 元素或屬性之值，為請求的型別。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)