---
title: ReadToFollowing()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest, bis ein Element mit dem angegebenen qualifizierten Namen gefunden wird.
type: docs
weight: 898
url: /de/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) Methode

Liest, bis ein Element mit dem angegebenen qualifizierten Namen gefunden wird.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des Elements. |

### Rückgabewert

**true** wenn ein passendes Element gefunden wird; andernfalls **false** und [XmlReader](../) ist im End-Datei-Zustand.

## XmlReader::ReadToFollowing(String, String) Methode

Liest, bis ein Element mit dem angegebenen lokalen Namen und Namespace-URI gefunden wird.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Elements. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Elements. |

### Rückgabewert

**true** wenn ein passendes Element gefunden wird; andernfalls **false** und [XmlReader](../) ist im End-Datei-Zustand.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)