---
title: RemoveAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt ein Attribut anhand seines Namens.
type: docs
weight: 235
url: /de/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) Methode


Entfernt ein Attribut anhand seines Namens.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name des zu entfernenden Attributs. Dies ist ein qualifizierter Name. Er wird mit dem **get_Name**-Wert des passenden Knotens abgeglichen. |

## XmlElement::RemoveAttribute(String, String) Methode


Entfernt ein Attribut mit dem angegebenen lokalen Namen und Namespace-URI. (Wenn das entfernte Attribut einen Standardwert hat, wird dieser sofort ersetzt).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des zu entfernenden Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des zu entfernenden Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)