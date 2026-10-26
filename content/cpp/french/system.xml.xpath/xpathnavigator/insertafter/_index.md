---
title: InsertAfter()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un objet XmlWriter utilisé pour créer un nouveau nœud frère après le nœud actuellement sélectionné.
type: docs
weight: 898
url: /fr/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() méthode

Renvoie un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère après le nœud actuellement sélectionné.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Valeur de retour

Un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud frère après le nœud actuellement sélectionné.

## XPathNavigator::InsertAfter(String) méthode

Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant la chaîne XML spécifiée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La chaîne de données XML pour le nouveau nœud frère. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) méthode

Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant le contenu XML de l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objet [XmlReader](../../../system.xml/xmlreader/) positionné sur les données XML du nouveau nœud frère. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) méthode

Crée un nouveau nœud frère après le nœud actuellement sélectionné en utilisant les nœuds de l'objet [XPathNavigator](../) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objet [XPathNavigator](../) positionné sur le nœud à ajouter comme nouveau nœud frère. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)