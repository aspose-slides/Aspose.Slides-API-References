---
title: GetAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur de l'attribut avec le nom spécifié.
type: docs
weight: 443
url: /fr/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) méthode

Renvoie la valeur de l'attribut avec le nom spécifié.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## XmlValidatingReader::GetAttribute(String, String) méthode

Renvoie la valeur de l'attribut avec le nom local et l'Uniform Resource Identifier (URI) de l'espace de noms spécifiés.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI de l'espace de noms de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé. Cette méthode ne déplace pas le lecteur.

## XmlValidatingReader::GetAttribute(int32_t) méthode

Renvoie la valeur de l'attribut avec l'index spécifié.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. L'index commence à zéro. (Le premier attribut a l'index 0.) |

### Valeur de retour

La valeur de l'attribut spécifié.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)