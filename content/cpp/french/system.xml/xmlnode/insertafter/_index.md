---
title: InsertAfter()
second_title: Référence API Aspose.Slides pour C++
description: Insère le nœud spécifié immédiatement après le nœud de référence spécifié.
type: docs
weight: 391
url: /fr/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) méthode

Insère le nœud spécifié immédiatement après le nœud de référence spécifié.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Le nœud à insérer. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | Le nœud de référence. **newChild** est placé après **refChild**. |

### Valeur de retour

Le nœud en cours d'insertion.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)