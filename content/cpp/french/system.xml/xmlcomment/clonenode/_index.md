---
title: CloneNode()
second_title: Référence API Aspose.Slides pour C++
description: Crée une copie de ce nœud.
type: docs
weight: 40
url: /fr/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) méthode

Crée une copie de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner uniquement le nœud lui-même. Comme les nœuds de commentaire n’ont pas d’enfants, le nœud cloné inclut toujours le contenu texte, quel que soit le paramètre. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlComment](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)