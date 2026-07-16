---
title: get_BaseURI()
second_title: Référence de l'API Aspose.Slides for C++
description: Renvoie l'identifiant uniforme de ressource (URI) de base du nœud.
type: docs
weight: 183
url: /fr/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() méthode


Renvoie l'identifiant uniforme de ressource (URI) de base du nœud.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Valeur de retour

L'emplacement à partir duquel le nœud a été chargé ou [String::Empty](../../../system/string/empty/) si le nœud n'a pas d'URI de base. Les nœuds [Attribute](../../../system/attribute/) ont le même URI de base que leur élément propriétaire. Si un nœud d'attribut ne possède pas d'élément propriétaire, get_BaseURI renvoie [String::Empty](../../../system/string/empty/).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlAttribute](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)