---
title: GetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Attributs mit dem angegebenen Namen zurück.
type: docs
weight: 209
url: /de/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) Methode

Gibt den Wert des Attributs mit dem angegebenen Namen zurück.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name des abzurufenden Attributs. Dies ist ein qualifizierter Name. Er wird mit dem **get_Name**-Wert des passenden Knotens verglichen. |

### Rückgabewert

Der Wert des angegebenen Attributs. Eine leere Zeichenkette wird zurückgegeben, wenn kein passendes Attribut gefunden wird oder das Attribut keinen angegebenen oder Standardwert hat.

## XmlElement::GetAttribute(String, String) Methode

Gibt den Wert des Attributs mit dem angegebenen lokalen Namen und Namespace-URI zurück.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des abzurufenden Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des abzurufenden Attributs. |

### Rückgabewert

Der Wert des angegebenen Attributs. Eine leere Zeichenkette wird zurückgegeben, wenn kein passendes Attribut gefunden wird oder das Attribut keinen angegebenen oder Standardwert hat.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)