---
title: get_LocalName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le nom local du nœud lorsqu'il est remplacé dans une classe dérivée.
type: docs
weight: 209
url: /fr/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() méthode

Renvoie le nom local du nœud, lorsqu'il est remplacé dans une classe dérivée.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### Valeur de retour

Le nom du nœud sans le préfixe. Par exemple, **LocalName** est **book** pour l'élément **<bk:book>**.

## Remarques

Le nom renvoyé dépend du [XmlNode::get_NodeType](../get_nodetype/) du nœud :

| Type | Nom |
| --- | --- |
| [Attribute](../../../system/attribute/)| The local name of the attribute. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | The document type name. |
| Element | The local name of the element. |
| Entity | The name of the entity. |
| EntityReference | The name of the entity referenced. |
| Notation | The notation name. |
| ProcessingInstruction | The target of the processing instruction. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)