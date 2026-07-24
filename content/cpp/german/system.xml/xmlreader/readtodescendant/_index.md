---
title: ReadToDescendant()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XmlReader zum nächsten Nachfahren-Element mit dem angegebenen qualifizierten Namen.
type: docs
weight: 911
url: /de/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) Methode

Verschiebt den [XmlReader](../) zum nächsten Nachfahren-Element mit dem angegebenen qualifizierten Namen.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Elements, zu dem Sie wechseln möchten. |

### Rückgabewert

**true** wenn ein passendes Nachfahren-Element gefunden wird; sonst **false**. Wenn kein passendes Kind-Element gefunden wird, ist der [XmlReader](../) auf dem End-Tag ([XmlReader::get_NodeType](../get_nodetype/) Wert ist [XmlNodeType::EndElement](../../xmlnodetype/)) des Elements positioniert. Wenn der [XmlReader](../) nicht auf einem Element positioniert ist, wenn [XmlReader::ReadToDescendant(String)](./) aufgerufen wurde, gibt diese Methode **false** zurück und die Position des [XmlReader](../) wird nicht geändert.

## XmlReader::ReadToDescendant(String, String) Methode

Verschiebt den [XmlReader](../) zum nächsten Nachfahren-Element mit dem angegebenen lokalen Namen und Namespace-URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Elements, zu dem Sie wechseln möchten. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Elements, zu dem Sie wechseln möchten. |

### Rückgabewert

**true** wenn ein passendes Nachfahren-Element gefunden wird; sonst **false**. Wenn kein passendes Kind-Element gefunden wird, ist der [XmlReader](../) auf dem End-Tag ([XmlReader::get_NodeType](../get_nodetype/) Wert ist [XmlNodeType::EndElement](../../xmlnodetype/)) des Elements positioniert. Wenn der [XmlReader](../) nicht auf einem Element positioniert ist, wenn [XmlReader::ReadToDescendant(String,String)](./) aufgerufen wurde, gibt diese Methode **false** zurück und die Position des [XmlReader](../) wird nicht geändert.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)