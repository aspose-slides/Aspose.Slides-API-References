---
title: get_OldValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur d'origine du nœud.
type: docs
weight: 53
url: /fr/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() méthode

Renvoie la valeur d'origine du nœud.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### Valeur de retour

La valeur d'origine du nœud. Cette méthode renvoie **nullptr** si le nœud n'est ni un attribut ni un nœud texte, ou si le nœud est en cours d'insertion. Si elle est appelée dans un événement **XmlDocument::NodeChanging**, **get_OldValue** renvoie la valeur actuelle du nœud qui sera remplacée si la modification réussit. Si elle est appelée dans un événement **XmlDocument::NodeChanged**, **get_OldValue** renvoie la valeur du nœud avant la modification.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)