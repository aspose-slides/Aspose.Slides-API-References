---
title: ReadElementContentAs()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementets innehåll som den begärda typen.
type: docs
weight: 586
url: /sv/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod


Läser elementets innehåll som den begärda typen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typen av värdet som ska returneras. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ett [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-objekt som används för att lösa alla namnrymdsprefix som är relaterade till typkonvertering. |

### Returvärde

Elementets innehåll konverterat till det begärda typade objektet.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metod


Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar den aktuella elementets, och läser sedan elementets innehåll som den begärda typen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typen av värdet som ska returneras. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ett [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-objekt som används för att lösa alla namnrymdsprefix som är relaterade till typkonvertering. |
| localName | [String](../../../system/string/) | Det lokala namnet på elementet. |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI för elementet. |

### Returvärde

Elementets innehåll konverterat till det begärda typade objektet.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klass [XmlReader](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)