---
title: ConformanceLevel
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die Menge an Eingabe- oder Ausgabeüberprüfungen an, die die XmlReader- und XmlWriter-Objekte durchführen.
type: docs
weight: 625
url: /de/system.xml/conformancelevel/
---
## ConformanceLevel Enum

Gibt die Menge an Eingabe- oder Ausgabeüberprüfungen an, die die Objekte [XmlReader](../xmlreader/) und [XmlWriter](../xmlwriter/) durchführen.

```cpp
enum class ConformanceLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Das [XmlReader](../xmlreader/)- oder [XmlWriter](../xmlwriter/)-Objekt erkennt automatisch, ob eine Dokument- oder Fragment-Überprüfung durchgeführt werden soll, und führt die entsprechende Prüfung durch. Wenn Sie ein anderes [XmlReader](../xmlreader/)- oder [XmlWriter](../xmlwriter/)-Objekt einhüllen, führt das äußere Objekt keine zusätzliche Konformitätsprüfung durch. Die Konformitätsprüfung bleibt dem zugrunde liegenden Objekt überlassen. |
| Fragment | 1 | Die XML-Daten sind ein [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) gemäß der Definition der W3C. Dieses Konformitätsniveau repräsentiert ein XML-Dokument, das möglicherweise kein Wurzelelement hat, aber ansonsten wohlgeformt ist. Dieses Prüfungsniveau stellt sicher, dass der zu lesende oder schreibende Stream von jedem Prozessor als [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) verarbeitet werden kann. |
| Document | 2 | Die XML-Daten entsprechen den Regeln für ein wohlgeformtes [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) gemäß der Definition der W3C. Dieses Prüfungsniveau stellt sicher, dass der zu lesende oder schreibende Stream von jedem Prozessor als [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) verarbeitet werden kann. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)