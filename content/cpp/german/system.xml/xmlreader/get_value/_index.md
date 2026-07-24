---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird in einer abgeleiteten Klasse überschrieben, gibt den Textwert des aktuellen Knotens zurück.
type: docs
weight: 92
url: /de/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() Methode

When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Rückgabewert

Der zurückgegebene Wert hängt vom [XmlReader::get_NodeType](../get_nodetype/) Wert des Knotens ab.

## Anmerkungen

Die folgende Tabelle listet Knotentypen auf, die einen zurückzugebenden Wert haben. Alle anderen Knotentypen geben [String::Empty](../../../system/string/empty/) zurück.

| Knotentyp | Wert |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Der Wert des Attributs. |
| `CDATA`| Der Inhalt des CDATA-Abschnitts. |
| `Comment`| Der Inhalt des Kommentars. |
| `DocumentType`| Das interne Subset. |
| `ProcessingInstruction`| Der gesamte Inhalt, ohne das Ziel. |
| `SignificantWhitespace`| Der Leerraum zwischen Markup in einem gemischten Inhaltsmodell. |
| `[Text](../../../system.text/)`| Der Inhalt des Textknotens. |
| `Whitespace`| Der Leerraum zwischen Markup. |
| [XmlDeclaration](../../xmldeclaration/)| Der Inhalt der Deklaration. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)