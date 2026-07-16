---
title: RemoveAttributeNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime l'XmlAttribute spécifié.
type: docs
weight: 274
url: /fr/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) méthode


Supprime le [XmlAttribute](../../xmlattribute/) spécifié.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Le nœud [XmlAttribute](../../xmlattribute/) à supprimer. Si l'attribut supprimé a une valeur par défaut, elle est immédiatement remplacée. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) supprimé ou **nullptr** si **oldAttr** n'est pas un nœud d'attribut du [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) méthode


Supprime le [XmlAttribute](../../xmlattribute/) spécifié par le nom local et l'URI d'espace de noms. (Si l'attribut supprimé a une valeur par défaut, elle est immédiatement remplacée).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) supprimé ou **nullptr** si le [XmlElement](../) ne possède pas de nœud d'attribut correspondant.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)