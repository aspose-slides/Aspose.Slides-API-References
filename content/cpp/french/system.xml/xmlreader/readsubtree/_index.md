---
title: ReadSubtree()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une nouvelle instance XmlReader qui peut être utilisée pour lire le nœud actuel et tous ses descendants.
type: docs
weight: 963
url: /fr/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() méthode


Renvoie une nouvelle instance [XmlReader](../) qui peut être utilisée pour lire le nœud actuel et tous ses descendants.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### Valeur de retour

Une nouvelle instance de lecteur XML définie sur [ReadState::Initial](../../readstate/). L’appel de la méthode [XmlReader::Read](../read/) positionne le nouveau lecteur sur le nœud qui était actuellement sélectionné avant l’appel à la méthode [XmlReader::ReadSubtree](./).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)