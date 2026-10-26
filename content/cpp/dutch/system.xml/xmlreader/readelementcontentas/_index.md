---
title: ReadElementContentAs()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud van het element als het opgegeven type.
type: docs
weight: 586
url: /nl/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Leest de inhoud van het element als het opgevraagde type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het type van de waarde die moet worden geretourneerd. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Een [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object dat wordt gebruikt om alle namespace-prefixes met betrekking tot typeconversie op te lossen. |

### Retourwaarde

De elementinhoud geconverteerd naar het opgevraagde getypte object.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method

Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens de inhoud van het element als het opgevraagde type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het type van de waarde die moet worden geretourneerd. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Een [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object dat wordt gebruikt om alle namespace-prefixes met betrekking tot typeconversie op te lossen. |
| localName | [String](../../../system/string/) | De lokale naam van het element. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element. |

### Retourwaarde

De elementinhoud geconverteerd naar het opgevraagde getypte object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)