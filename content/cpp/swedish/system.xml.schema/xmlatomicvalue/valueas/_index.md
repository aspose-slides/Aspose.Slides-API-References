---
title: ValueAs()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det validerade XML-elementets eller attributets värde som den angivna typen med hjälp av IXmlNamespaceResolver-objektet som specificeras för att lösa namnrymdsprefix.
type: docs
weight: 144
url: /sv/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod


Returnerar det validerade XML-elementets eller attributets värde som den angivna typen med hjälp av [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som specificeras för att lösa namnrymdsprefix.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Den typ som det validerade XML-elementets eller attributets värde ska returneras som. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objektet som används för att lösa namnrymdsprefix. |

### Returvärde

Värdet på det validerade XML-elementet eller attributet som den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klass [XmlAtomicValue](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)