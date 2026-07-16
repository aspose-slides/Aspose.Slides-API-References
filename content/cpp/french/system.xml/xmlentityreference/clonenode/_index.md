---
title: CloneNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un duplicata de ce nœud.
type: docs
weight: 92
url: /fr/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) method

Crée un duplicata de ce nœud.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | **bool** | true pour cloner récursivement le sous-arbre sous le nœud spécifié ; false pour cloner uniquement le nœud lui-même. Pour les nœuds [XmlEntityReference](../), cette méthode renvoie toujours un nœud de référence d'entité sans enfants. Le texte de remplacement est défini lorsque le nœud est inséré dans un parent. |

### Valeur de retour

Le nœud cloné.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)