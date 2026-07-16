---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de ce nœud.
type: docs
weight: 53
url: /fr/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) method


Crée une copie de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** pour cloner récursivement le sous-arbre sous le nœud spécifié ; **false** pour cloner uniquement le nœud lui-même. Comme les nœuds CDATA n’ont pas d’enfants, quel que soit le paramètre, le nœud cloné inclura toujours le contenu des données. |

### Return Value

Le nœud cloné.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)