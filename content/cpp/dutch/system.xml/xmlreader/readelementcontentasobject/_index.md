---
title: ReadElementContentAsObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het huidige element en retourneert de inhoud als een Object.
type: docs
weight: 469
url: /nl/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() methode

Leest het huidige element en retourneert de inhoud als een [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Returnwaarde

Een verpakt object van het meest geschikte type. De [XmlReader::get_ValueType](../get_valuetype/) waarde bepaalt het geschikte type. Als de inhoud getypeerd is als een lijsttype, retourneert deze methode een array van verpakte objecten van het geschikte type.

## XmlReader::ReadElementContentAsObject(String, String) methode

Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het element. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element. |

### Returnwaarde

Een verpakt object van het meest geschikte type. De [XmlReader::get_ValueType](../get_valuetype/) waarde bepaalt het geschikte type. Als de inhoud getypeerd is als een lijsttype, retourneert deze methode een array van verpakte objecten van het geschikte type.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)