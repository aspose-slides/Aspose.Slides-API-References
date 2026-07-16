---
title: get_Name()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, elle récupère le nom qualifié du nœud actuel.
type: docs
weight: 27
url: /fr/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() méthode


Lorsqu'elle est remplacée dans une classe dérivée, elle récupère le nom qualifié du nœud actuel.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Valeur de retour

Le nom qualifié du nœud actuel. Par exemple, **Name** est **bk:book** pour l'élément **<bk:book>**.
## Remarques



Le nom renvoyé dépend de la valeur [XmlReader::get_NodeType](../get_nodetype/) du nœud. Les types de nœuds suivants renvoient les valeurs indiquées. Tous les autres types de nœuds renvoient une chaîne vide. 

| Type de nœud | Nom |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Le nom de l'attribut. |
| `DocumentType`| Le nom du type de document. |
| `Element`| Le nom de la balise. |
| `EntityReference`| Le nom de l'entité référencée. |
| `ProcessingInstruction`| La cible de l'instruction de traitement. |
| [XmlDeclaration](../../xmldeclaration/)| La chaîne littérale `xml`. |


## Voir également

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)