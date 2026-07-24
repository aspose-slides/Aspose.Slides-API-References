---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Textwert des aktuellen Knotens zurück.
type: docs
weight: 79
url: /de/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() Methode

Gibt den Textwert des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Rückgabewert

Der zurückgegebene Wert hängt vom [XmlTextReader::get_NodeType](../get_nodetype/)-Wert des Knotens ab.

## Bemerkungen

Die folgende Tabelle listet Knotentypen auf, die einen zurückzugebenden Wert besitzen. Alle anderen Knotentypen geben [String::Empty](../../../system/string/empty/) zurück.

| Knotentyp | Wert |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der Wert des Attributs. |
| CDATA| Der Inhalt des CDATA-Abschnitts. |
| Comment| Der Inhalt des Kommentars. |
| DocumentType| Das interne Subset. |
| ProcessingInstruction| Der gesamte Inhalt, ohne das Ziel. |
| SignificantWhitespace| Der Leerraum innerhalb eines `xml:space='preserve'`-Bereichs. |
| [Text](../../../system.text/)| Der Inhalt des Textknotens. |
| Whitespace| Der Leerraum zwischen Markup. |
| [XmlDeclaration](../../xmldeclaration/)| Der Inhalt der Deklaration. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)