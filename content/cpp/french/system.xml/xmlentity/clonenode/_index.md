---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un duplicata de ce nœud. Les nœuds d'entité ne peuvent pas être clonés. L'appel de cette méthode sur un objet XmlEntity lève une exception.
type: docs
weight: 170
url: /fr/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) méthode

Crée un duplicata de ce nœud. Les nœuds d'entité ne peuvent pas être clonés. Appeler cette méthode sur un objet [XmlEntity](../) lève une exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner seulement le nœud lui-même. |

### Valeur de retour

Une copie du [XmlNode](../../xmlnode/) à partir duquel la méthode est appelée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [XmlNode](../../xmlnode/)
* classe [XmlEntity](../)
* espace de noms [System::Xml](../../)
* bibliothèque [Aspose.Slides](../../../)