---
title: get_NewValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la nouvelle valeur du nœud.
type: docs
weight: 66
url: /fr/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() méthode


Renvoie la nouvelle valeur du nœud.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Valeur de retour

La nouvelle valeur du nœud. Cette méthode renvoie **nullptr** si le nœud n'est ni un attribut ni un nœud texte, ou si le nœud est en cours de suppression. Si elle est appelée dans un événement **XmlDocument::NodeChanging**, **get_NewValue** renvoie la valeur du nœud si le changement réussit. Si elle est appelée dans un événement **XmlDocument::NodeChanged**, **get_NewValue** renvoie la valeur actuelle du nœud.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)