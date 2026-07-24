---
title: ReadToNextSibling()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XmlReader zum nächsten Geschwisterelement mit dem angegebenen qualifizierten Namen.
type: docs
weight: 924
url: /de/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) Methode

Verschiebt den [XmlReader](../) zum nächsten Geschwisterelement mit dem angegebenen qualifizierten Namen.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Geschwisterelements, zu dem Sie springen möchten. |

### Rückgabewert

**true** wenn ein passendes Geschwisterelement gefunden wird; andernfalls **false**. Wenn kein passendes Geschwisterelement gefunden wird, ist der [XmlReader](../) am End-Tag ([XmlReader::get_NodeType](../get_nodetype/)-Wert ist [XmlNodeType::EndElement](../../xmlnodetype/)) des übergeordneten Elements positioniert.

## XmlReader::ReadToNextSibling(String, String) Methode

Verschiebt den [XmlReader](../) zum nächsten Geschwisterelement mit dem angegebenen lokalen Namen und dem Namespace-URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Geschwisterelements, zu dem Sie springen möchten. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Geschwisterelements, zu dem Sie springen möchten. |

### Rückgabewert

**true** wenn ein passendes Geschwisterelement gefunden wird; andernfalls **false**. Wenn kein passendes Geschwisterelement gefunden wird, ist der [XmlReader](../) am End-Tag ([XmlReader::get_NodeType](../get_nodetype/)-Wert ist [XmlNodeType::EndElement](../../xmlnodetype/)) des übergeordneten Elements positioniert.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)