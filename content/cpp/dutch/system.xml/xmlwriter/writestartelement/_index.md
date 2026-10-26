---
title: WriteStartElement()
second_title: Aspose.Slides voor C++ API Referentie
description: Wanneer deze in een afgeleide klasse wordt overschreven, schrijft deze de opgegeven start-tag en koppelt deze aan de opgegeven namespace.
type: docs
weight: 92
url: /nl/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) methode

Wanneer deze methode in een afgeleide klasse wordt overschreven, schrijft deze de opgegeven start-tag en koppelt deze aan de opgegeven namespace.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het element. |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het element moet worden gekoppeld. Als deze namespace reeds in scope is en een gekoppeld prefix heeft, schrijft de schrijver dat prefix automatisch ook. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) methode

Wanneer deze methode in een afgeleide klasse wordt overschreven, schrijft deze de opgegeven start-tag en koppelt deze aan de opgegeven namespace en prefix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Het namespace-prefix van het element. |
| localName | const [String](../../../system/string/)\& | De lokale naam van het element. |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het element moet worden gekoppeld. |

## XmlWriter::WriteStartElement(const String\&) methode

Wanneer deze methode in een afgeleide klasse wordt overschreven, schrijft deze een start-tag met de opgegeven lokale naam.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het element. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)