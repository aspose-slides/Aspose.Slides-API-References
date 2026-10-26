---
title: ValueAs()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar objektets värde som den angivna typen.
type: docs
weight: 131
url: /sv/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metod

Returnerar objektets värde som den angivna typen.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typen att returnera objektets värde som. |

### Returvärde

Värdet på objektet i den begärda typen.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod

När den åsidosätts i en avledd klass returnerar den objektets värde som den typ som anges med [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typen att returnera objektets värde som. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix. |

### Returvärde

Värdet på objektet i den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XPathItem](../)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)