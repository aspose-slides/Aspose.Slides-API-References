---
title: get_Name()
second_title: Référence de l'API Aspose.Slides for C++
description: Renvoie le nom qualifié du nœud, lorsqu'il est redéfini dans une classe dérivée.
type: docs
weight: 1
url: /fr/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() méthode

Returns the qualified name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### Valeur de retour

Le nom qualifié du nœud.

## Remarques

Le nom retourné dépend du [XmlNode::get_NodeType](../get_nodetype/) du nœud:

| Type | Nom |
| --- | --- |
| [Attribute](../../../system/attribute/)| Le nom qualifié de l'attribut. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Le nom du type de document. |
| Element | Le nom qualifié de l'élément. |
| Entity | Le nom de l'entité. |
| EntityReference | Le nom de l'entité référencée. |
| Notation | Le nom de la notation. |
| ProcessingInstruction | La cible de l'instruction de traitement. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)