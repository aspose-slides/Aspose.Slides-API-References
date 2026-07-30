---
title: ValueAs()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu položky jako zadaný typ.
type: docs
weight: 131
url: /cs/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metoda

Vrací hodnotu položky jako zadaný typ.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, ve kterém se má vrátit hodnota položky. |

### Návratová hodnota

Hodnota položky v požadovaném typu.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Při přepsání v odvozené třídě vrací hodnotu položky ve typu určeném pomocí objektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) sloužícího k rozpoznání předpon jmenných prostorů.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, ve kterém se má vrátit hodnota položky. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozpoznání předpon jmenných prostorů. |

### Návratová hodnota

Hodnota položky v požadovaném typu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XPathItem](../)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)