---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird in einer abgeleiteten Klasse überschrieben, gibt den qualifizierten Namen des aktuellen Knotens zurück.
type: docs
weight: 27
url: /de/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() Methode


Wird in einer abgeleiteten Klasse überschrieben, gibt den qualifizierten Namen des aktuellen Knotens zurück.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Rückgabewert

Der qualifizierte Name des aktuellen Knotens. Zum Beispiel ist **Name** **bk:book** für das Element **<bk:book>**.

## Bemerkungen



Der zurückgegebene Name hängt vom [XmlReader::get_NodeType](../get_nodetype/)-Wert des Knotens ab. Die folgenden Knotentypen geben die angegebenen Werte zurück. Alle anderen Knotentypen geben einen leeren String zurück. 

| Node type | Name |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Der Name des Attributs. |
| `DocumentType`| Der Dokumenttypname. |
| `Element`| Der Tag-Name. |
| `EntityReference`| Der Name der referenzierten Entität. |
| `ProcessingInstruction`| Das Ziel der Verarbeitungsanweisung. |
| [XmlDeclaration](../../xmldeclaration/)| Der Literal-String `xml`. |


## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)