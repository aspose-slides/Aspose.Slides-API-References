---
title: SetAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt den Wert des Attributs mit dem angegebenen Namen.
type: docs
weight: 222
url: /de/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) method


Setzt den Wert des Attributs mit dem angegebenen Namen.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name des Attributs, das erstellt oder geändert werden soll. Dies ist ein qualifizierter Name. Wenn der Name einen Doppelpunkt enthält, wird er in Präfix- und lokalen Namensanteil zerlegt. |
| value | [String](../../../system/string/) | Der für das Attribut zu setzende Wert. |

## XmlElement::SetAttribute(String, String, String) method


Setzt den Wert des Attributs mit dem angegebenen lokalen Namen und Namespace-URI.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |
| value | [String](../../../system/string/) | Der für das Attribut zu setzende Wert. |

### Return Value

Der Attributwert.

## See Also

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)