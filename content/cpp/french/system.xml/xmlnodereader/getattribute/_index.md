---
title: GetAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur de l'attribut portant le nom spécifié.
type: docs
weight: 287
url: /fr/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) méthode


Renvoie la valeur de l'attribut portant le nom spécifié.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## XmlNodeReader::GetAttribute(String, String) méthode


Renvoie la valeur de l'attribut portant le nom local et l'URI de l'espace de noms spécifiés.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI de l'espace de noms de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## XmlNodeReader::GetAttribute(int32_t) méthode


Renvoie la valeur de l'attribut à l'index spécifié.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | L'index de l'attribut. L'index commence à zéro. (Le premier attribut a l'index 0.) |

### Valeur de retour

La valeur de l'attribut spécifié.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)