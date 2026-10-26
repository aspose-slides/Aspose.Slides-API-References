---
title: ReadAttributeValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Analyse la valeur de l'attribut en un ou plusieurs nœuds Text, EntityReference ou EndEntity.
type: docs
weight: 508
url: /fr/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() méthode

Analyse la valeur de l'attribut en un ou plusieurs **[Text](../../../system.text/)**, **EntityReference**, ou **EndEntity** nœuds.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Valeur de retour

**true** si des nœuds sont à renvoyer. **false** si le lecteur n’est pas positionné sur un nœud d’attribut lors de l’appel initial ou si toutes les valeurs d’attribut ont été lues. Un attribut vide, tel que **misc=\"\"**, renvoie **true** avec un seul nœud dont la valeur est [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)