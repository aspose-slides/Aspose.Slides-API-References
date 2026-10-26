---
title: ReadAttributeValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, analyse la valeur de l'attribut en un ou plusieurs nœuds Text, EntityReference ou EndEntity.
type: docs
weight: 677
url: /fr/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() méthode


Lorsqu'elle est redéfinie dans une classe dérivée, analyse la valeur de l'attribut en un ou plusieurs nœuds **[Text](../../../system.text/)**, **EntityReference**, ou **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Valeur de retour

**true** si des nœuds sont à retourner. **false** si le lecteur n'est pas positionné sur un nœud d'attribut lorsque l'appel initial est effectué ou si toutes les valeurs d'attribut ont été lues. Un attribut vide, tel que **misc=\"\"**, renvoie **true** avec un seul nœud dont la valeur est [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)