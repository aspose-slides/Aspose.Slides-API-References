---
title: InsertBefore()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un objet XmlWriter utilisé pour créer un nouveau nœud frère avant le nœud actuellement sélectionné.
type: docs
weight: 911
url: /fr/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() méthode

Renvoie un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère avant le nœud actuellement sélectionné.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Valeur de retour

Un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère avant le nœud actuellement sélectionné.

## XPathNavigator::InsertBefore(String) méthode

Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant la chaîne XML spécifiée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La chaîne de données XML pour le nouveau nœud frère. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) méthode

Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant le contenu XML de l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objet [XmlReader](../../../system.xml/xmlreader/) positionné sur les données XML du nouveau nœud frère. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) méthode

Crée un nouveau nœud frère avant le nœud actuellement sélectionné en utilisant les nœuds du [XPathNavigator](../) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objet [XPathNavigator](../) positionné sur le nœud à ajouter comme nouveau nœud frère. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)