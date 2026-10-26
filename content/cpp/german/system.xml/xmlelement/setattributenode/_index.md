---
title: SetAttributeNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das angegebene XmlAttribute hinzu.
type: docs
weight: 261
url: /de/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) Methode

Fügt das angegebene [XmlAttribute](../../xmlattribute/) hinzu.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Der [XmlAttribute](../../xmlattribute/) Knoten, der zur Attributsammlung dieses Elements hinzugefügt wird. |

### Rückgabewert

Wenn das Attribut ein vorhandenes Attribut mit demselben Namen ersetzt, wird das alte [XmlAttribute](../../xmlattribute/) zurückgegeben; andernfalls wird **nullptr** zurückgegeben.

## XmlElement::SetAttributeNode(String, String) Methode

Fügt das angegebene [XmlAttribute](../../xmlattribute/) hinzu.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Der [XmlAttribute](../../xmlattribute/) zum Hinzufügen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)