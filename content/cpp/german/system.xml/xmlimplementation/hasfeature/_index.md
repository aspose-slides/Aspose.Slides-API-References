---
title: HasFeature()
second_title: Aspose.Slides für C++ API Referenz
description: Testet, ob die Document Object Model (DOM)-Implementierung ein bestimmtes Feature implementiert.
type: docs
weight: 14
url: /de/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) Methode

Testet, ob die Document [Object](../../../system/object/) Model (DOM) Implementierung ein bestimmtes Feature implementiert.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Der Paketname des zu testenden Features. Dieser Name ist nicht groß-/kleinschreibungssensitiv. |
| strVersion | const [String](../../../system/string/)\& | Dies ist die Versionsnummer des zu testenden Paketnamens. Wenn die Version nicht angegeben ist (**nullptr**), führt die Unterstützung irgendeiner Version des Features dazu, dass die Methode **true** zurückgibt. |

### Rückgabewert

**true**, wenn das Feature in der angegebenen Version implementiert ist; andernfalls **false**.

## Hinweise

Die folgende Tabelle zeigt die Kombinationen, die dazu führen, dass **HasFeature** **true** zurückgibt. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlImplementation](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)