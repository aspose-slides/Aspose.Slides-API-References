---
title: get_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur texte du nœud actuel.
type: docs
weight: 79
url: /fr/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() méthode

Renvoie la valeur texte du nœud actuel.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Valeur de retour

La valeur renvoyée dépend du [XmlNodeReader::get_NodeType](../get_nodetype/) du nœud.

## Remarques

Le tableau suivant répertorie les types de nœuds qui possèdent une valeur à renvoyer. Tous les autres types de nœuds renvoient [String::Empty](../../../system/string/empty/). 

| Type de nœud | Valeur |
| --- | --- |
| [Attribute](../../../system/attribute/)| La valeur de l'attribut. |
| CDATA| Le contenu de la section CDATA. |
| Comment| Le contenu du commentaire. |
| DocumentType| Le sous-ensemble interne. |
| ProcessingInstruction| L'intégralité du contenu, à l'exclusion de la cible. |
| SignificantWhitespace| L'espace blanc entre les balises dans un modèle de contenu mixte. |
| [Text](../../../system.text/)| Le contenu du nœud texte. |
| Whitespace| L'espace blanc entre les balises. |
| [XmlDeclaration](../../xmldeclaration/)| Le contenu de la déclaration. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)