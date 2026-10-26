---
title: get_Name()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie le nom qualifié du nœud actuel.
type: docs
weight: 14
url: /fr/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() méthode


Renvoie le nom qualifié du nœud actuel.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Valeur de retour

Le nom qualifié du nœud actuel. Par exemple, **Name** est **bk:book** pour l’élément **<bk:book>**.
## Remarques



Le nom retourné dépend de la valeur [XmlNodeReader::get_NodeType](../get_nodetype/) du nœud. Les types de nœuds suivants renvoient les valeurs indiquées. Tous les autres types de nœuds renvoient une chaîne vide. 

| Type de nœud | Nom |
| --- | --- |
| [Attribute](../../../system/attribute/)| Le nom de l'attribut. |
| DocumentType| Le nom du type de document. |
| Element| Le nom de la balise. |
| EntityReference| Le nom de l'entité référencée. |
| ProcessingInstruction| La cible de l'instruction de traitement. |
| [XmlDeclaration](../../xmldeclaration/)| La chaîne littérale `xml`. |


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)