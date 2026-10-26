---
title: GetAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur de l'attribut avec le nom spécifié.
type: docs
weight: 495
url: /fr/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) méthode

Renvoie la valeur de l'attribut ayant le nom spécifié.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom complet de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## XmlTextReader::GetAttribute(String, String) méthode

Renvoie la valeur de l'attribut ayant le nom local et l'URI d'espace de noms spécifiés.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé. Cette méthode ne fait pas avancer le lecteur.

## XmlTextReader::GetAttribute(int32_t) méthode

Renvoie la valeur de l'attribut ayant l'index spécifié.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. L'index commence à zéro. (Le premier attribut a l'index 0.) |

### Valeur de retour

La valeur de l'attribut spécifié.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)