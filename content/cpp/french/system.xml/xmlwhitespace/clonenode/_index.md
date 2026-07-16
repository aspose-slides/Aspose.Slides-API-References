---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée un duplicata de ce nœud.
type: docs
weight: 79
url: /fr/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) méthode

Crée un duplicata de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié; **false** pour cloner uniquement le nœud lui-même. Pour les nœuds d’espace blanc, le nœud cloné inclut toujours la valeur de données, quel que soit le paramètre. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlWhitespace](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)