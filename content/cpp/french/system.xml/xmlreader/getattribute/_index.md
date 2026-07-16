---
title: GetAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lorsqu'elle est remplacée dans une classe dérivée, récupère la valeur de l'attribut avec la valeur XmlReader::get_Name spécifiée."
type: docs
weight: 599
url: /fr/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, récupère la valeur de l'attribut avec la valeur [XmlReader::get_Name](../get_name/) spécifiée.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé ou que la valeur est [String::Empty](../../../system/string/empty/), **nullptr** est renvoyé.

## XmlReader::GetAttribute(String, String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, récupère la valeur de l'attribut avec les valeurs [XmlReader::get_LocalName](../get_localname/) et [XmlReader::get_NamespaceURI](../get_namespaceuri/) spécifiées.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI de l'espace de noms de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé ou que la valeur est [String::Empty](../../../system/string/empty/), **nullptr** est renvoyé. Cette méthode ne fait pas avancer le lecteur.

## XmlReader::GetAttribute(int32_t) méthode

Lorsqu'elle est remplacée dans une classe dérivée, récupère la valeur de l'attribut avec l'index spécifié.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. L'index commence à zéro. (Le premier attribut a l'index 0.) |

### Valeur de retour

La valeur de l'attribut spécifié. Cette méthode ne fait pas avancer le lecteur.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)