---
title: XmlNodeType
second_title: Référence API Aspose.Slides pour C++
description: Spécifie le type de nœud.
type: docs
weight: 833
url: /fr/system.xml/xmlnodetype/
---
## XmlNodeType enum

Spécifie le type de nœud.

```cpp
enum class XmlNodeType
```

### Valeurs

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Ceci est renvoyé par le [XmlReader](../xmlreader/) si une méthode **Read** n'a pas été appelée. |
| Element | 1 | Un élément (par exemple, **<item>**). |
| Attribute | 2 | Un attribut (par exemple, **id='123'**). |
| Text | 3 | Le contenu texte d'un nœud. Un nœud [XmlNodeType::Text](./) ne peut pas avoir de nœuds enfants. Il peut apparaître comme nœud enfant des nœuds [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) et [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Une section CDATA (par exemple, **my escaped text**). |
| EntityReference | 5 | Une référence à une entité (par exemple, **&num;**). |
| Entity | 6 | Une déclaration d'entité (par exemple, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Une instruction de traitement (par exemple, **<?pi test?>**). |
| Comment | 8 | Un commentaire (par exemple, ****). |
| Document | 9 | Un objet document qui, en tant que racine de l'arbre du document, donne accès à l'intégralité du document XML. |
| DocumentType | 10 | La déclaration du type de document, indiquée par la balise suivante (par exemple, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Un fragment de document. |
| Notation | 12 | Une notation dans la déclaration du type de document (par exemple, **<!NOTATION...>**). |
| Whitespace | 13 | Espace blanc entre les balises. |
| SignificantWhitespace | 14 | Espace blanc entre les balises dans un modèle de contenu mixte ou espace blanc dans la portée **xml:space=\"preserve\"**. |
| EndElement | 15 | Une balise de fin d'élément (par exemple, ****). |
| EndEntity | 16 | Renvoyé lorsque [XmlReader](../xmlreader/) atteint la fin du remplacement d'entité à la suite d'un appel à [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | La déclaration XML (par exemple, **<?xml version='1.0'?>**). Le nœud [XmlNodeType::XmlDeclaration](./) doit être le premier nœud du document. Il ne peut pas avoir d'enfants. C'est un enfant du nœud [XmlNodeType::Document](./). Il peut avoir des attributs qui fournissent les informations de version et d'encodage. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)