---
title: InsertAfter()
second_title: Référence API Aspose.Slides pour C++
description: Insère le nœud spécifié immédiatement après le nœud de référence spécifié.
type: docs
weight: 222
url: /fr/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) méthode

Insère le nœud spécifié immédiatement après le nœud de référence spécifié.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Le [XmlNode](../../xmlnode/) à insérer. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Le [XmlNode](../../xmlnode/) qui est le nœud de référence. Le **newChild** est placé après le **refChild**. |

### Valeur de retour

Le [XmlNode](../../xmlnode/) inséré.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)