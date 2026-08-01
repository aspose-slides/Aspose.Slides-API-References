---
title: ChangeType()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert de opgegeven waarde, waarvan het type een van de geldige representaties is van het XML-schema type dat wordt vertegenwoordigd door de XmlSchemaDatatype, naar het opgegeven runtijdtype.
type: docs
weight: 66
url: /nl/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) methode

Converteert de opgegeven waarde, waarvan het type een van de geldige representaties is van het XML-schemasoort dat wordt vertegenwoordigd door de [XmlSchemaDatatype](../), naar het opgegeven runtijdtype.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | De invoerwaarde die moet worden geconverteerd naar het opgegeven type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Het doeltype waaraan de invoerwaarde moet worden geconverteerd. |

### Retourwaarde

De geconverteerde invoerwaarde.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) methode

Converteert de opgegeven waarde, waarvan het type een van de geldige representaties is van het XML-schemasoort dat wordt vertegenwoordigd door de [XmlSchemaDatatype](../), naar het opgegeven runtijdtype met behulp van de [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) als de [XmlSchemaDatatype](../) het **xs:QName**-type vertegenwoordigt of een daarvan afgeleid type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | De invoerwaarde die moet worden geconverteerd naar het opgegeven type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Het doeltype waaraan de invoerwaarde moet worden geconverteerd. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Een [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) die wordt gebruikt voor het oplossen van namespace-prefixen. Dit is alleen nuttig als de [XmlSchemaDatatype](../) het **xs:QName**-type vertegenwoordigt of een daarvan afgeleid type. |

### Retourwaarde

De geconverteerde invoerwaarde.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlSchemaDatatype](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)