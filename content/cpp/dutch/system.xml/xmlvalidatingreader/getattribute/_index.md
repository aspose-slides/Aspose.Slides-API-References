---
title: GetAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het attribuut met de opgegeven naam.
type: docs
weight: 443
url: /nl/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) methode


Retourneert de waarde van het attribuut met de opgegeven naam.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, wordt **nullptr** geretourneerd.

## XmlValidatingReader::GetAttribute(String, String) methode


Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace Uniform Resource Identifier (URI).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, wordt **nullptr** geretourneerd. Deze methode verplaatst de lezer niet.

## XmlValidatingReader::GetAttribute(int32_t) methode


Retourneert de waarde van het attribuut met de opgegeven index.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. De index is nul-gebaseerd. (Het eerste attribuut heeft index 0.) |

### Retourwaarde

De waarde van het opgegeven attribuut.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)