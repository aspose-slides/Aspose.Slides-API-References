---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des Knotens zurück.
type: docs
weight: 14
url: /de/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() Methode

Gibt den Wert des Knotens zurück.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Rückgabewert

Der zurückgegebene Wert hängt vom [XmlNode::get_NodeType](../get_nodetype/) des Knotens ab: 

| Typ | Wert |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der Wert des Attributs. |
| CDATASection | Der Inhalt des CDATA-Abschnitts. |
| Comment | Der Inhalt des Kommentars. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Sie können die XmlElement::InnerText oder [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) Werte verwenden, um auf den Wert des Elementknotens zuzugreifen. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Der gesamte Inhalt ohne das Ziel. |
| [Text](../../../system.text/)| Der Inhalt des Textknotens. |
| SignificantWhitespace | Die Leerzeichenzeichen. Leerzeichen können aus einem oder mehreren Leerzeichen, Wagenrückläufen, Zeilenumbrüchen oder Tabulatoren bestehen. |
| Whitespace | Die Leerzeichenzeichen. Leerzeichen können aus einem oder mehreren Leerzeichen, Wagenrückläufen, Zeilenumbrüchen oder Tabulatoren bestehen. |
| [XmlDeclaration](../../xmldeclaration/)| Der Inhalt der Deklaration (auch alles zwischen `<?xml` und `?>`). |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)