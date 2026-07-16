---
title: SetAttributeNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le XmlAttribute spécifié.
type: docs
weight: 261
url: /fr/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) méthode

Ajoute le [XmlAttribute](../../xmlattribute/) spécifié.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Le nœud [XmlAttribute](../../xmlattribute/) à ajouter à la collection d'attributs de cet élément. |

### Valeur de retour

Si l'attribut remplace un attribut existant portant le même nom, l'ancien [XmlAttribute](../../xmlattribute/) est renvoyé; sinon, **nullptr** est renvoyé.

## XmlElement::SetAttributeNode(String, String) méthode

Ajoute le [XmlAttribute](../../xmlattribute/) spécifié.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI de l'espace de noms de l'attribut. |

### Valeur de retour

Le [XmlAttribute](../../xmlattribute/) à ajouter.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)