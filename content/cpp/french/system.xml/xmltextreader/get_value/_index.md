---
title: get_Value()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur texte du nœud actuel.
type: docs
weight: 79
url: /fr/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() méthode

Renvoie la valeur texte du nœud actuel.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Valeur de retour

La valeur renvoyée dépend de la valeur [XmlTextReader::get_NodeType](../get_nodetype/) du nœud.

## Remarques

Le tableau suivant répertorie les types de nœuds qui ont une valeur à renvoyer. Tous les autres types de nœuds renvoient [String::Empty](../../../system/string/empty/). 

| Type de nœud | Valeur |
| --- | --- |
| [Attribute](../../../system/attribute/) | La valeur de l'attribut. |
| CDATA | Le contenu de la section CDATA. |
| Comment | Le contenu du commentaire. |
| DocumentType | Le sous-ensemble interne. |
| ProcessingInstruction | L'intégralité du contenu, à l'exclusion de la cible. |
| SignificantWhitespace | L'espace blanc à l'intérieur d'une portée `xml:space='preserve'`. |
| [Text](../../../system.text/) | Le contenu du nœud texte. |
| Whitespace | L'espace blanc entre les balises. |
| [XmlDeclaration](../../xmldeclaration/) | Le contenu de la déclaration. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)