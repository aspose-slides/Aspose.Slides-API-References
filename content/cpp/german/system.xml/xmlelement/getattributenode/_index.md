---
title: GetAttributeNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das XmlAttribute mit dem angegebenen Namen zurück.
type: docs
weight: 248
url: /de/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) method


Gibt das [XmlAttribute](../../xmlattribute/) mit dem angegebenen Namen zurück.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name des abzurufenden Attributs. Dies ist ein qualifizierter Name. Er wird mit dem Wert **get_Name** des passenden Knotens abgeglichen. |

### Return Value

Das angegebene [XmlAttribute](../../xmlattribute/) oder **nullptr**, wenn kein passendes Attribut gefunden wurde.

## XmlElement::GetAttributeNode(String, String) method


Gibt das [XmlAttribute](../../xmlattribute/) mit dem angegebenen lokalen Namen und dem Namespace-URI zurück.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Return Value

Das angegebene [XmlAttribute](../../xmlattribute/) oder **nullptr**, wenn kein passendes Attribut gefunden wurde.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)