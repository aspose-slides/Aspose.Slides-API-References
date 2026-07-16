---
title: CloneNode()
second_title: Référence d'API Aspose.Slides pour C++
description: Crée une copie de ce nœud.
type: docs
weight: 157
url: /fr/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) méthode


Crée une copie de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner uniquement le nœud lui-même. Parce que les nœuds [XmlDeclaration](../) n’ont pas d’enfants, le nœud cloné inclut toujours la valeur des données, quelle que soit la configuration du paramètre. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDeclaration](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)