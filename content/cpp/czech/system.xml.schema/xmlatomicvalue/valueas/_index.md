---
title: ValueAs()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací hodnotu ověřeného XML prvku nebo atributu jako určený typ pomocí objektu IXmlNamespaceResolver určeného k rozřešení předpon jmenných prostorů.
type: docs
weight: 144
url: /cs/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Vrací hodnotu ověřeného XML prvku nebo atributu jako určený typ pomocí objektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) určeného k rozřešení předpon jmenných prostorů.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ, který se použije k vrácení hodnoty ověřeného XML prvku nebo atributu. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozřešení předpon jmenných prostorů. |

### Návratová hodnota

Hodnota ověřeného XML prvku nebo atributu jako požadovaný typ.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XmlAtomicValue](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)