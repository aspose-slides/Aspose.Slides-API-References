---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het knooppunt.
type: docs
weight: 14
url: /nl/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() methode


Retourneert de waarde van het knooppunt.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Retourwaarde

De geretourneerde waarde hangt af van de [XmlNode::get_NodeType](../get_nodetype/) van het knooppunt: 

| Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| De waarde van het attribuut. |
| CDATASection | De inhoud van de CDATA Section. |
| Comment | De inhoud van de opmerking. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Je kunt de XmlElement::InnerText of [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) waarden gebruiken om de waarde van het elementknooppunt te benaderen. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | De volledige inhoud, exclusief de target. |
| [Text](../../../system.text/)| De inhoud van het tekstknooppunt. |
| SignificantWhitespace | De witruimte-tekens. Witruimte kan bestaan uit een of meer spatie-tekens, carriage returns, line feeds, of tabs. |
| Whitespace | De witruimte-tekens. Witruimte kan bestaan uit een of meer spatie-tekens, carriage returns, line feeds, of tabs. |
| [XmlDeclaration](../../xmldeclaration/)| De inhoud van de declaratie (dat is alles tussen `<?xml and ?>`). |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)