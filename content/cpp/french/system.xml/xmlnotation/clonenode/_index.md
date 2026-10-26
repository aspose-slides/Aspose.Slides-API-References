---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un duplicata de ce nœud. Les nœuds de notation ne peuvent pas être clonés. Appeler cette méthode sur un objet XmlNotation lève une exception.
type: docs
weight: 118
url: /fr/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) méthode


Crée un duplicata de ce nœud. Les nœuds de notation ne peuvent pas être clonés. Appeler cette méthode sur un objet [XmlNotation](../) lève une exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié; **false** pour cloner uniquement le nœud lui-même. |

### Valeur de retour

Une copie [XmlNode](../../xmlnode/) du nœud à partir duquel la méthode est appelée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNotation](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)