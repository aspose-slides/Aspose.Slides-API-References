---
title: ValueAs()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den aktuella nodens värde som den angivna typen, med IXmlNamespaceResolver-objektet som anges för att lösa namnrymdsprefix.
type: docs
weight: 378
url: /sv/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod

Returnerar det aktuella nodens värde som den angivna typen, med [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som anges för att lösa namnrymdsprefix.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | The Type för att returnera det aktuella nodens värde som. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix. |

### Returvärde

Värdet av den aktuella noden som den begärda Type.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)