---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Textwert des aktuellen Knotens zurück.
type: docs
weight: 79
url: /de/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() Methode

Gibt den Textwert des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Rückgabewert

Der zurückgegebene Wert hängt vom XmlValidatingReader::NodeType des Knotens ab.

## Hinweise

Die folgende Tabelle listet Knotentypen auf, die einen zurückzugebenden Wert besitzen. Alle anderen Knotentypen geben [String::Empty](../../../system/string/empty/) zurück.

| Knotentyp | Wert |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der Wert des Attributs. |
| CDATA| Der Inhalt des CDATA-Abschnitts. |
| Comment| Der Inhalt des Kommentars. |
| DocumentType| Der interne Teilbereich. |
| ProcessingInstruction| Der gesamte Inhalt, ohne das Ziel. |
| SignificantWhitespace| Der Leerraum zwischen Markup in einem gemischten Inhaltsmodell. |
| [Text](../../../system.text/)| Der Inhalt des Textknotens. |
| Whitespace| Der Leerraum zwischen Markup. |
| [XmlDeclaration](../../xmldeclaration/)| Der Inhalt der Deklaration. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)