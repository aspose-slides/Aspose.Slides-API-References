---
title: XPathNodeType
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit les types de nœuds XPath qui peuvent être renvoyés par la classe XPathNavigator.
type: docs
weight: 157
url: /fr/system.xml.xpath/xpathnodetype/
---
## XPathNodeType énum


Defines the [XPath](../) node types that can be returned from the [XPathNavigator](../xpathnavigator/) class.

```cpp
enum class XPathNodeType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Root | 0 | Le nœud racine du document XML ou de l'arborescence de nœuds. |
| Element | 1 | Un élément, tel que **<element>**. |
| Attribute | 2 | Un attribut, tel que **id='123'**. |
| Namespace | 3 | Un espace de noms, tel que **xmlns=\"namespace\"**. |
| Text | 4 | Le contenu texte d'un nœud. Équivalent au Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) et aux types de nœuds CDATA. Contient au moins un caractère. |
| SignificantWhitespace | 5 | Un nœud contenant des caractères d'espacement et **xml:space** défini sur **preserve**. |
| Whitespace | 6 | Un nœud contenant uniquement des caractères d'espacement et aucun espace blanc significatif. Les caractères d'espacement sont **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Une instruction de traitement, telle que **<?pi test?>**. Cela n'inclut pas les déclarations XML, qui ne sont pas visibles par la classe [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Un commentaire, tel que ****. |
| All | 9 | N'importe lequel des types de nœuds XPathNodeType. |

## Voir aussi

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)