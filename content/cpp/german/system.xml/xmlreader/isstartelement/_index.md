---
title: IsStartElement()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ruft XmlReader::MoveToContent auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist."
type: docs
weight: 885
url: /de/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() Methode

Ruft [XmlReader::MoveToContent](../movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Rückgabewert

**true**, wenn [XmlReader::MoveToContent](../movetocontent/) ein Start-Tag oder ein leeres Element-Tag findet; **false**, wenn ein Knotentyp gefunden wurde, der nicht [XmlNodeType::Element](../../xmlnodetype/) ist.

## XmlReader::IsStartElement(String) Methode

Ruft [XmlReader::MoveToContent](../movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist und ob der [XmlReader::get_Name](../get_name/)-Wert des gefundenen Elements mit dem angegebenen Argument übereinstimmt.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der String, der mit dem **Name**-Wert des gefundenen Elements abgeglichen wird. |

### Rückgabewert

**true**, wenn der resultierende Knoten ein Element ist und der **Name**-Wert mit der angegebenen Zeichenkette übereinstimmt. **false**, wenn ein Knotentyp gefunden wurde, der nicht [XmlNodeType::Element](../../xmlnodetype/) ist, oder wenn der **Name**-Wert des Elements nicht mit der angegebenen Zeichenkette übereinstimmt.

## XmlReader::IsStartElement(String, String) Methode

Ruft [XmlReader::MoveToContent](../movetocontent/) auf und prüft, ob der aktuelle Inhaltsknoten ein Start-Tag oder ein leeres Element-Tag ist und ob die [XmlReader::get_LocalName](../get_localname/)- und [XmlReader::get_NamespaceURI](../get_namespaceuri/)-Werte des gefundenen Elements mit den angegebenen Zeichenketten übereinstimmen.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Der String, der mit dem **LocalName**-Wert des gefundenen Elements abgeglichen wird. |
| ns | [String](../../../system/string/) | Der String, der mit dem **NamespaceURI**-Wert des gefundenen Elements abgeglichen wird. |

### Rückgabewert

**true**, wenn der resultierende Knoten ein Element ist. **false**, wenn ein Knotentyp gefunden wurde, der nicht [XmlNodeType::Element](../../xmlnodetype/) ist, oder wenn die **LocalName**- und **NamespaceURI**-Werte des Elements nicht mit den angegebenen Zeichenketten übereinstimmen.

## Siehe auch

* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)