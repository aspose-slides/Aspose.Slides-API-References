---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, obtient la valeur de l'attribut avec l'index spécifié.
type: docs
weight: 612
url: /fr/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) méthode

Lorsqu'elle est remplacée dans une classe dérivée, obtient la valeur de l'attribut avec l'index spécifié.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **int32_t** | L'index de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié.

## XmlReader::idx_get(String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, obtient la valeur de l'attribut avec la valeur [XmlReader::get_Name](../get_name/) spécifiée.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom qualifié de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## XmlReader::idx_get(String, String) méthode

Lorsqu'elle est remplacée dans une classe dérivée, obtient la valeur de l'attribut avec les valeurs [XmlReader::get_LocalName](../get_localname/) et [XmlReader::get_NamespaceURI](../get_namespaceuri/) spécifiées.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom local de l'attribut. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'attribut. |

### Valeur de retour

La valeur de l'attribut spécifié. Si l'attribut n'est pas trouvé, **nullptr** est renvoyé.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)