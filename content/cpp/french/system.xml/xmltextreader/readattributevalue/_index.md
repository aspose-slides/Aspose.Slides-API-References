---
title: ReadAttributeValue()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Analyse la valeur de l'attribut en un ou plusieurs nœuds Text, EntityReference ou EndEntity.
type: docs
weight: 560
url: /fr/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() méthode

Analyse la valeur de l'attribut en un ou plusieurs nœuds **[Text](../../../system.text/)**, **EntityReference** ou **EndEntity**.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Valeur de retour

**true** si des nœuds sont à renvoyer. **false** si le lecteur n'est pas positionné sur un nœud d'attribut lors de l'appel initial ou si toutes les valeurs d'attribut ont été lues. Un attribut vide, tel que **misc=\"\"**, renvoie **true** avec un seul nœud dont la valeur est [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)