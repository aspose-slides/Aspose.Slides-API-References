---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie le premier élément enfant avec le XmlNode::get_Name spécifié."
type: docs
weight: 586
url: /fr/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) méthode

Renvoie le premier élément enfant avec le [XmlNode::get_Name](../get_name/) spécifié.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'élément à récupérer. |

### Valeur de retour

Le premier [XmlElement](../../xmlelement/) qui correspond au nom spécifié. Il renvoie **nullptr** s'il n'y a aucune correspondance.

## XmlNode::idx_get(String, String) méthode

Renvoie le premier élément enfant avec les valeurs [XmlNode::get_LocalName](../get_localname/) et [XmlNode::get_NamespaceURI](../get_namespaceuri/) spécifiées.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Le nom local de l'élément. |
| ns | [String](../../../system/string/) | L'URI de l'espace de noms de l'élément. |

### Valeur de retour

Le premier [XmlElement](../../xmlelement/) dont le **localname** et le **ns** correspondent. Il renvoie **nullptr** s'il n'y a aucune correspondance.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlElement](../../xmlelement/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)