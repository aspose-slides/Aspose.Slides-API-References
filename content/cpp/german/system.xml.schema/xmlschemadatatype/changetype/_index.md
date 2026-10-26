---
title: ChangeType()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen Wert, dessen Typ eine der gültigen Darstellungen des durch XmlSchemaDatatype dargestellten XML-Schemas ist, in den angegebenen Laufzeittyp.
type: docs
weight: 66
url: /de/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) Methode

Konvertiert den angegebenen Wert, dessen Typ eine der gültigen Darstellungen des durch [XmlSchemaDatatype](../) dargestellten XML-Schematyps ist, in den angegebenen Laufzeittyp.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Der Eingabewert, der in den angegebenen Typ konvertiert werden soll. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Der Zieltyp, in den der Eingabewert konvertiert werden soll. |

### Rückgabewert

Der konvertierte Eingabewert.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode

Konvertiert den angegebenen Wert, dessen Typ eine der gültigen Darstellungen des durch [XmlSchemaDatatype](../) dargestellten XML-Schematyps ist, in den angegebenen Laufzeittyp unter Verwendung von [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), falls [XmlSchemaDatatype](../) den Typ **xs:QName** oder einen davon abgeleiteten Typ darstellt.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Der Eingabewert, der in den angegebenen Typ konvertiert werden soll. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Der Zieltyp, in den der Eingabewert konvertiert werden soll. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Ein [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), das zum Auflösen von Namensraum-Präfixen verwendet wird. Dies ist nur nützlich, wenn [XmlSchemaDatatype](../) den Typ **xs:QName** oder einen davon abgeleiteten Typ darstellt. |

### Rückgabewert

Der konvertierte Eingabewert.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlSchemaDatatype](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)