---
title: InsertAfter()
second_title: Référence API Aspose.Slides pour C++
description: Insère l'attribut spécifié immédiatement après l'attribut de référence spécifié.
type: docs
weight: 66
url: /fr/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) méthode

Insère l'attribut spécifié immédiatement après l'attribut de référence spécifié.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attribut à insérer. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | L'attribut de référence. **newNode** est placé après le **refNode**. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) à insérer dans la collection.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)