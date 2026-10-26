---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, atomise la chaîne spécifiée et l'ajoute à la XmlNameTable.
type: docs
weight: 14
url: /fr/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) méthode

Lorsqu'elle est remplacée dans une classe dérivée, atomise la chaîne spécifiée et l'ajoute à la [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Le tableau de caractères contenant le nom à ajouter. |
| offset | **int32_t** | Indice à base zéro dans le tableau indiquant le premier caractère du nom. |
| length | **int32_t** | Le nombre de caractères dans le nom. |

## Valeur de retour

La nouvelle chaîne atomisée ou celle existante si elle existe déjà. Si la longueur est zéro, [String::Empty](../../../system/string/empty/) est renvoyée.

## XmlNameTable::Add(const String\&) méthode

Lorsqu'elle est remplacée dans une classe dérivée, atomise la chaîne spécifiée et l'ajoute à la [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Le nom à ajouter. |

## Valeur de retour

La nouvelle chaîne atomisée ou celle existante si elle existe déjà.

## Voir également

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)