---
title: get_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur du nœud.
type: docs
weight: 14
url: /fr/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() méthode

Renvoie la valeur du nœud.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Valeur de retour

La valeur renvoyée dépend de la [XmlNode::get_NodeType](../get_nodetype/) du nœud : 

| Type | Valeur |
| --- | --- |
| [Attribute](../../../system/attribute/)| La valeur de l'attribut. |
| CDATASection | Le contenu de la section CDATA. |
| Comment | Le contenu du commentaire. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Vous pouvez utiliser XmlElement::InnerText ou les valeurs [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) pour accéder à la valeur du nœud élément. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | L'intégralité du contenu, à l'exception de la cible. |
| [Text](../../../system.text/)| Le contenu du nœud texte. |
| SignificantWhitespace | Les caractères d'espacement. L'espace peut consister en un ou plusieurs espaces, retours chariot, sauts de ligne ou tabulations. |
| Whitespace | Les caractères d'espacement. L'espace peut consister en un ou plusieurs espaces, retours chariot, sauts de ligne ou tabulations. |
| [XmlDeclaration](../../xmldeclaration/)| Le contenu de la déclaration (c’est-à-dire tout ce qui se trouve entre `<?xml and ?>`). |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)