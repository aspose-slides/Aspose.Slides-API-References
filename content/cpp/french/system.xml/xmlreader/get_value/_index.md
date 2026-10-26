---
title: get_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, renvoie la valeur texte du nœud actuel.
type: docs
weight: 92
url: /fr/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() méthode


Lorsqu'elle est remplacée dans une classe dérivée, renvoie la valeur texte du nœud actuel.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Valeur de retour

La valeur renvoyée dépend de la valeur [XmlReader::get_NodeType](../get_nodetype/) du nœud.
## Remarques



Le tableau suivant répertorie les types de nœuds qui possèdent une valeur à retourner. Tous les autres types de nœuds renvoient [String::Empty](../../../system/string/empty/). 

| Type de nœud | Valeur |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| La valeur de l'attribut. |
| `CDATA`| Le contenu de la section CDATA. |
| `Comment`| Le contenu du commentaire. |
| `DocumentType`| Le sous-ensemble interne. |
| `ProcessingInstruction`| L'intégralité du contenu, à l'exclusion de la cible. |
| `SignificantWhitespace`| Les espaces blancs entre les balises dans un modèle de contenu mixte. |
| `[Text](../../../system.text/)`| Le contenu du nœud texte. |
| `Whitespace`| Les espaces blancs entre les balises. |
| [XmlDeclaration](../../xmldeclaration/)| Le contenu de la déclaration. |


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)