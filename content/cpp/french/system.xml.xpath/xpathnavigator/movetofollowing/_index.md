---
title: MoveToFollowing()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace le XPathNavigator vers l'élément dont le nom local et l'URI d'espace de noms sont spécifiés dans l'ordre du document.
type: docs
weight: 703
url: /fr/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) méthode

Déplace le [XPathNavigator](../) vers l'élément dont le nom local et l'URI d'espace de noms sont spécifiés dans l'ordre du document.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément. |

### Valeur de retour

**true** si le [XPathNavigator](../) a été déplacé avec succès ; sinon, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) méthode

Déplace le [XPathNavigator](../) vers l'élément dont le nom local et l'URI d'espace de noms sont spécifiés, jusqu'à la limite spécifiée, dans l'ordre du document.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'élément. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | L'objet [XPathNavigator](../) positionné sur la limite de l'élément que le [XPathNavigator](../) actuel ne dépassera pas lors de la recherche de l'élément suivant. |

### Valeur de retour

**true** si le [XPathNavigator](../) a été déplacé avec succès ; sinon, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) méthode

Déplace le [XPathNavigator](../) vers l'élément suivant du XPathNodeType spécifié dans l'ordre du document.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType de l'élément. Le XPathNodeType ne peut pas être [XPathNodeType::Attribute](../../xpathnodetype/) ou [XPathNodeType::Namespace](../../xpathnodetype/). |

### Valeur de retour

**true** si le [XPathNavigator](../) a été déplacé avec succès ; sinon, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) méthode

Déplace le [XPathNavigator](../) vers l'élément suivant du XPathNodeType spécifié, jusqu'à la limite spécifiée, dans l'ordre du document.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Le XPathNodeType de l'élément. Le XPathNodeType ne peut pas être [XPathNodeType::Attribute](../../xpathnodetype/) ou [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | L'objet [XPathNavigator](../) positionné sur la limite de l'élément que le [XPathNavigator](../) actuel ne dépassera pas lors de la recherche de l'élément suivant. |

### Valeur de retour

**true** si le [XPathNavigator](../) a été déplacé avec succès ; sinon, **false**.

## Voir aussi

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Espace de noms [System::Xml::XPath](../../)
* Bibliothèque [Aspose.Slides](../../../)