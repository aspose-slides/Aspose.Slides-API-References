---
title: PrependChild()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un objet XmlWriter utilisé pour créer un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel.
type: docs
weight: 872
url: /fr/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() méthode


Renvoie un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Valeur de retour

Un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel.

## XPathNavigator::PrependChild(String) méthode


Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant la chaîne XML spécifiée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La chaîne de données XML pour le nouveau nœud enfant. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) méthode


Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant le contenu XML de l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objet [XmlReader](../../../system.xml/xmlreader/) positionné sur les données XML du nouveau nœud enfant. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) méthode


Crée un nouveau nœud enfant au début de la liste des nœuds enfants du nœud actuel en utilisant les nœuds de l'objet [XPathNavigator](../) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objet [XPathNavigator](../) positionné sur le nœud à ajouter comme nouveau nœud enfant. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)