---
title: ChangeType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadanou hodnotu, jejíž typ je jednou z platných reprezentací typu XML schématu reprezentovaného třídou XmlSchemaDatatype, na určený typ za běhu.
type: docs
weight: 66
url: /cs/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metoda


Převádí zadanou hodnotu, jejíž typ je jednou z platných reprezentací typu XML schématu reprezentovaného [XmlSchemaDatatype](../), na zadaný typ za běhu.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vstupní hodnota, která se má převést na zadaný typ. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Cílový typ, na který se vstupní hodnota převede. |

### Návratová hodnota

Převedená vstupní hodnota.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda


Převádí zadanou hodnotu, jejíž typ je jednou z platných reprezentací typu XML schématu reprezentovaného [XmlSchemaDatatype](../), na zadaný typ za běhu pomocí [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), pokud [XmlSchemaDatatype](../) představuje typ **xs:QName** nebo typ z něj odvozený.
```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vstupní hodnota, která se má převést na zadaný typ. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Cílový typ, na který se má vstupní hodnota převést. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozlišování předpon jmenných prostorů. To je užitečné pouze v případě, že [XmlSchemaDatatype](../) představuje typ **xs:QName** nebo typ z něj odvozený. |

### Návratová hodnota

Převedená vstupní hodnota.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlSchemaDatatype](../)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)