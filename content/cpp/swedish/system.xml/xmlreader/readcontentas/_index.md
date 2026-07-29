---
title: ReadContentAs()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet som ett objekt av den angivna typen.
type: docs
weight: 456
url: /sv/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod

Läser innehållet som ett objekt av den angivna typen.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typen av värdet som ska returneras. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ett [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-objekt som används för att lösa eventuella namnrymdspräfix som är relaterade till typkonvertering. Till exempel kan detta användas när ett [XmlQualifiedName](../../xmlqualifiedname/)-objekt konverteras till en **xs:string**. Detta värde kan vara **nullptr**. |

### Returvärde

Den sammanslagna textinnehållet eller attributvärdet konverterat till den begärda typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)