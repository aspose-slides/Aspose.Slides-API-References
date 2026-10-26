---
title: Get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, récupère la chaîne atomisée contenant les mêmes caractères que la plage de caractères spécifiée dans le tableau donné.
type: docs
weight: 1
url: /fr/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) méthode


When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Le tableau de caractères contenant le nom à rechercher. |
| offset | **int32_t** | L'indice basé sur zéro dans le tableau spécifiant le premier caractère du nom. |
| length | **int32_t** | Le nombre de caractères du nom. |

### Valeur de retour

The atomized string or **nullptr** if the string has not already been atomized. If **length** is zero, [String::Empty](../../../system/string/empty/) is returned.

## XmlNameTable::Get(const String\&) méthode


When overridden in a derived class, gets the atomized string containing the same value as the specified string.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Le nom à rechercher. |

### Valeur de retour

The atomized string or **nullptr** if the string has not already been atomized.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)