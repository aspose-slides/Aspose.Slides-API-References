---
title: get_Name()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie le nom complet du nœud actuel.
type: docs
weight: 14
url: /fr/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() méthode

Renvoie le nom complet du nœud actuel.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Valeur de retour

Le nom complet du nœud actuel. Par exemple, **Name** est **bk:book** pour l'élément **<bk:book>**.

## Remarques

Le nom renvoyé dépend du XmlValidatingReader::NodeType du nœud. Les types de nœuds suivants renvoient les valeurs indiquées. Tous les autres types de nœuds renvoient une chaîne vide.

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
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)