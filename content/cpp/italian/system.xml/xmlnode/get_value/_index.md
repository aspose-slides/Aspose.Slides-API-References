---
title: get_Value()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore del nodo.
type: docs
weight: 14
url: /it/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metodo


Restituisce il valore del nodo.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Valore di ritorno

Il valore restituito dipende dal [XmlNode::get_NodeType](../get_nodetype/) del nodo: 

| Tipo | Valore |
| --- | --- |
| [Attribute](../../../system/attribute/)| Il valore dell'attributo. |
| CDATASection | Il contenuto della sezione CDATA. |
| Comment | Il contenuto del commento. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. È possibile usare XmlElement::InnerText o i valori [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) per accedere al valore del nodo elemento. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | L'intero contenuto escluso il target. |
| [Text](../../../system.text/)| Il contenuto del nodo di testo. |
| SignificantWhitespace | I caratteri di spazio bianco. Lo spazio bianco può consistere in uno o più caratteri di spazio, ritorni a capo, avanzamenti di riga o tabulazioni. |
| Whitespace | I caratteri di spazio bianco. Lo spazio bianco può consistere in uno o più caratteri di spazio, ritorni a capo, avanzamenti di riga o tabulazioni. |
| [XmlDeclaration](../../xmldeclaration/)| Il contenuto della dichiarazione (cioè, tutto tra `<?xml` e `?>`). |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)