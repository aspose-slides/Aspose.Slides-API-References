---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den qualifizierten Namen des aktuellen Knotens zurück.
type: docs
weight: 14
url: /de/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() Methode

Gibt den qualifizierten Namen des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### Rückgabewert

Der qualifizierte Name des aktuellen Knotens. Zum Beispiel ist **Name** **bk:book** für das Element **<bk:book>**.

## Hinweise

Der zurückgegebene Name hängt vom [XmlNodeReader::get_NodeType](../get_nodetype/) Wert des Knotens ab. Die folgenden Knotentypen geben die aufgelisteten Werte zurück. Alle anderen Knotentypen geben eine leere Zeichenkette zurück.

| Knotentyp | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der Name des Attributs. |
| DocumentType| Der Dokumenttyp-Name. |
| Element| Der Tag-Name. |
| EntityReference| Der Name der referenzierten Entität. |
| ProcessingInstruction| Das Ziel der Verarbeitungsanweisung. |
| [XmlDeclaration](../../xmldeclaration/)| Die literal Zeichenkette `xml`. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)