---
title: GetAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het attribuut met de opgegeven naam.
type: docs
weight: 287
url: /nl/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) methode

Retourneert de waarde van het attribuut met de opgegeven naam.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, **nullptr** wordt geretourneerd.

## XmlNodeReader::GetAttribute(String, String) methode

Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace-URI.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, **nullptr** wordt geretourneerd.

## XmlNodeReader::GetAttribute(int32_t) methode

Retourneert de waarde van het attribuut met de opgegeven index.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | De index van het attribuut. De index is nulgebaseerd. (Het eerste attribuut heeft index 0.) |

### Retourwaarde

De waarde van het opgegeven attribuut.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)