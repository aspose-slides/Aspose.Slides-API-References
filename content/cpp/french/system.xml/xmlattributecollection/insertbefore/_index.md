---
title: InsertBefore()
second_title: Référence API Aspose.Slides pour C++
description: Insère l'attribut spécifié immédiatement avant l'attribut de référence spécifié.
type: docs
weight: 53
url: /fr/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) méthode


Insère l'attribut spécifié immédiatement avant l'attribut de référence spécifié.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attribut à insérer. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attribut de référence. **newNode** est placé avant le **refNode**. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) à insérer dans la collection.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)