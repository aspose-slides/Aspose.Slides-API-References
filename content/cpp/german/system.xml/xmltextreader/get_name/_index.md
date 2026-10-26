---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den qualifizierten Namen des aktuellen Knotens zurück.
type: docs
weight: 14
url: /de/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() Methode


Gibt den qualifizierten Namen des aktuellen Knotens zurück.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Rückgabewert

Der qualifizierte Name des aktuellen Knotens. Zum Beispiel ist **Name** **bk:book** für das Element **<bk:book>**.
## Bemerkungen



Der zurückgegebene Name hängt vom [XmlTextReader::get_NodeType](../get_nodetype/)-Wert des Knotens ab. Die folgenden Knotentypen geben die aufgeführten Werte zurück. Alle anderen Knotentypen geben eine leere Zeichenkette zurück. 

| Knotentyp | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| Der Name des Attributs. |
| DocumentType| Der Name des Dokumenttyps. |
| Element| Der Name des Tags. |
| EntityReference| Der Name der referenzierten Entität. |
| ProcessingInstruction| Das Ziel der Verarbeitungsanweisung. |
| [XmlDeclaration](../../xmldeclaration/)| Die literale Zeichenkette `xml`. |


## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)