---
title: idx_get()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'attribut avec l'index spécifié.
type: docs
weight: 1
url: /fr/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) méthode


Renvoie l'attribut avec l'index spécifié.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. |

### Valeur de retour

L'attribut à l'index spécifié.

## XmlAttributeCollection::idx_get(const String\&) méthode


Renvoie l'attribut avec le nom spécifié.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom qualifié de l'attribut. |

### Valeur de retour

L'attribut avec le nom spécifié. Si l'attribut n'existe pas, cette méthode renvoie **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) méthode


Renvoie l'attribut avec le nom local et l'Uniform Resource Identifier (URI) de l'espace de noms spécifiés.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'attribut. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

L'attribut avec le nom local et l'URI d'espace de noms spécifiés. Si l'attribut n'existe pas, cette méthode renvoie **nullptr**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)