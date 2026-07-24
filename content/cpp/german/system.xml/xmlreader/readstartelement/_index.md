---
title: ReadStartElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob der aktuelle Knoten ein Element ist, und rückt den Reader zum nächsten Knoten vor.
type: docs
weight: 846
url: /de/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() Methode

Überprüft, ob der aktuelle Knoten ein Element ist, und rückt den Reader zum nächsten Knoten vor.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) Methode

Überprüft, ob der aktuelle Inhaltsknoten ein Element mit dem angegebenen [XmlReader::get_Name](../get_name/)-Wert ist und rückt den Reader zum nächsten Knoten vor.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Elements. |

## XmlReader::ReadStartElement(String, String) Methode

Überprüft, ob der aktuelle Inhaltsknoten ein Element mit den angegebenen [XmlReader::get_LocalName](../get_localname/)- und [XmlReader::get_NamespaceURI](../get_namespaceuri/)-Werten ist und rückt den Reader zum nächsten Knoten vor.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Der lokale Name des Elements. |
| ns | [String](../../../system/string/) | Der Namespace-URI des Elements. |

## Siehe auch

* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)