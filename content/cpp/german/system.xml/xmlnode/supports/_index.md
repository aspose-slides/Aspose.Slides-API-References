---
title: Supports()
second_title: Aspose.Slides für C++ API-Referenz
description: Prüft, ob die DOM-Implementierung ein bestimmtes Feature implementiert.
type: docs
weight: 482
url: /de/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) Methode


Testet, ob die DOM-Implementierung ein bestimmtes Feature unterstützt.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Der Paketname des zu testenden Features. Dieser Name ist nicht case-sensitive. |
| version | [String](../../../system/string/) | Die Versionsnummer des zu testenden Paketnamens. Wenn die Version nicht angegeben ist (null), führt die Unterstützung irgendeiner Version des Features dazu, dass die Methode **true** zurückgibt. |

### Rückgabewert

**true** wenn das Feature in der angegebenen Version implementiert ist; andernfalls **false**.

## Bemerkungen



Die folgende Tabelle beschreibt die Kombinationen, die **true** zurückgeben. 

| Merkmal | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Siehe Auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)