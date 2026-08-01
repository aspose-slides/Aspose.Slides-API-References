---
title: ParseValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, valideert de string die is opgegeven tegen een ingebouwd of door de gebruiker gedefinieerd simpel type.
type: docs
weight: 53
url: /nl/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) methode

Wanneer overschreven in een afgeleide klasse, valideert de **string** die is opgegeven tegen een ingebouwd of door de gebruiker gedefinieerd simpel type.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | [String](../../../system/string/) | De **string** om te valideren tegen het simpele type. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | De [XmlNameTable](../../../system.xml/xmlnametable/) die moet worden gebruikt voor atomisatie tijdens het parsen van de **string** als dit [XmlSchemaDatatype](../) object het **xs:NCName** type vertegenwoordigt. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Het [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object dat moet worden gebruikt tijdens het parsen van de **string** als dit [XmlSchemaDatatype](../) object het **xs:QName** type vertegenwoordigt. |

### Retourwaarde

Een [Object](../../../system/object/) die veilig kan worden gecast naar het type dat wordt geretourneerd door de [XmlSchemaDatatype::get_ValueType](../get_valuetype/) oproep.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNameTable](../../../system.xml/xmlnametable/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XmlSchemaDatatype](../)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)