---
title: AppendChild()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un objet XmlWriter utilisé pour créer un ou plusieurs nouveaux nœuds enfants à la fin de la liste des nœuds enfants du nœud actuel.
type: docs
weight: 885
url: /fr/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() méthode

Renvoie un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer un ou plusieurs nouveaux nœuds enfants à la fin de la liste des nœuds enfants du nœud actuel.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Valeur de retour

Un objet [XmlWriter](../../../system.xml/xmlwriter/) utilisé pour créer de nouveaux nœuds enfants à la fin de la liste des nœuds enfants du nœud actuel.

## XPathNavigator::AppendChild(String) méthode

Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant la chaîne de données XML spécifiée.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La chaîne de données XML pour le nouveau nœud enfant. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) méthode

Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant le contenu XML de l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un objet [XmlReader](../../../system.xml/xmlreader/) positionné sur les données XML du nouveau nœud enfant. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) méthode

Crée un nouveau nœud enfant à la fin de la liste des nœuds enfants du nœud actuel en utilisant les nœuds du [XPathNavigator](../) spécifié.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un objet [XPathNavigator](../) positionné sur le nœud à ajouter comme nouveau nœud enfant. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)