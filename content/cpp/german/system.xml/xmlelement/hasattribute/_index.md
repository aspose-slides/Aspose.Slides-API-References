---
title: HasAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der aktuelle Knoten ein Attribut mit dem angegebenen Namen hat.
type: docs
weight: 300
url: /de/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) Methode

Bestimmt, ob der aktuelle Knoten ein Attribut mit dem angegebenen Namen hat.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name des zu findenden Attributs. Dies ist ein qualifizierter Name. Er wird mit dem **get_Name**-Wert des passenden Knotens verglichen. |

### Rückgabewert

**true**, wenn der aktuelle Knoten das angegebene Attribut hat; andernfalls **false**.

## XmlElement::HasAttribute(String, String) Methode

Bestimmt, ob der aktuelle Knoten ein Attribut mit dem angegebenen lokalen Namen und Namespace-URI hat.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des zu findenden Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des zu findenden Attributs. |

### Rückgabewert

**true**, wenn der aktuelle Knoten das angegebene Attribut hat; andernfalls **false**.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)