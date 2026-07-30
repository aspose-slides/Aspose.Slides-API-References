---
title: ValueAs()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu aktuálního uzlu jako zadaný Type za použití objektu IXmlNamespaceResolver určeného k rozlišení předpon jmenných prostorů.
type: docs
weight: 378
url: /cs/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Vrací hodnotu aktuálního uzlu jako zadaný Type, přičemž používá objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) určený k rozlišení předpon jmenných prostorů.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, kterým se má vrátit hodnota aktuálního uzlu. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozlišení předpon jmenných prostorů. |

### Návratová hodnota

Hodnota aktuálního uzlu jako požadovaný Type.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)