---
title: XPathNodeType
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert die XPath-Knotentypen, die von der Klasse XPathNavigator zurückgegeben werden können.
type: docs
weight: 157
url: /de/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definiert die [XPath](../) Knotentypen, die von der Klasse [XPathNavigator](../xpathnavigator/) zurückgegeben werden können.

```cpp
enum class XPathNodeType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Root | 0 | Der Wurzelknoten des XML-Dokuments oder des Knotensbaums. |
| Element | 1 | Ein Element, z. B. **<element>**. |
| Attribute | 2 | Ein Attribut, z. B. **id='123'**. |
| Namespace | 3 | Ein Namespace, z. B. **xmlns="namespace"**. |
| Text | 4 | Der Textinhalt eines Knotens. Entspricht dem Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) und den CDATA-Knotentypen. Enthält mindestens ein Zeichen. |
| SignificantWhitespace | 5 | Ein Knoten mit Leerzeichenzeichen und **xml:space** auf **preserve** gesetzt. |
| Whitespace | 6 | Ein Knoten, der nur Leerzeichenzeichen enthält und keinen signifikanten Leerraum hat. Leerzeichenzeichen sind **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Eine Verarbeitungsanweisung, z. B. **<?pi test?>**. Dies schließt XML-Deklarationen nicht ein, die für die Klasse [XPathNavigator](../xpathnavigator/) nicht sichtbar sind. |
| Comment | 8 | Ein Kommentar, z. B. ****. |
| All | 9 | Beliebiger der XPathNodeType-Knotentypen. |

## Siehe auch

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)