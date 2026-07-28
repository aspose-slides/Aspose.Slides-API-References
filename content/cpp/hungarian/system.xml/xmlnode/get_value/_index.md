---
title: get_Value()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a csomópont értékét.
type: docs
weight: 14
url: /hu/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metódus

Visszaadja a csomópont értékét.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Visszatérési érték

A visszaadott érték a csomópont [XmlNode::get_NodeType](../get_nodetype/)-jától függ:

| Típus | Érték |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum értéke. |
| CDATASection | A CDATA szakasz tartalma. |
| Comment | A megjegyzés tartalma. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Az XmlElement::InnerText vagy a [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) értékek használhatók az elem csomópont értékének eléréséhez. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | A teljes tartalom a célpont nélkül. |
| [Text](../../../system.text/)| A szövegcsomópont tartalma. |
| SignificantWhitespace | A szóköz karakterek. A szóköz egy vagy több szóköz karakterből, sortörésből, új sor karakterből vagy tabulátorból állhat. |
| Whitespace | A szóköz karakterek. A szóköz egy vagy több szóköz karakterből, sortörésből, új sor karakterből vagy tabulátorból állhat. |
| [XmlDeclaration](../../xmldeclaration/)| A deklaráció tartalma (azaz minden a `<?xml and ?>` között). |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNode](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)