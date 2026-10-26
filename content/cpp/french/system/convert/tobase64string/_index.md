---
title: ToBase64String()
second_title: Référence API Aspose.Slides for C++
description: Encode en base-64 les éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne.
type: docs
weight: 40
url: /fr/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) méthode


Le Base-64 encode les éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets à encoder |
| insert_line_breaks | **bool** | Indique si des caractères de saut de ligne doivent être insérés dans la chaîne de sortie après chaque groupe de 76 caractères base-64 |

### Valeur de retour

La chaîne contenant la représentation encodée en base-64 du tableau d'entrée

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) méthode


Le Base-64 encode une plage d'éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets contenant la plage d'éléments à encoder |
| offset_in | int | Un indice d'un élément du tableau d'entrée où commence la plage à encoder |
| length | int | La longueur de la plage d'éléments à encoder |
| insert_line_breaks | **bool** | Indique si des caractères de saut de ligne doivent être insérés dans la chaîne de sortie après chaque groupe de 76 caractères base-64 |

### Valeur de retour

La chaîne contenant la représentation encodée en base-64 de la plage d'éléments du tableau d'entrée

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) méthode


Le Base-64 encode les éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets à encoder |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Spécifie les options de formatage des données encodées en base-64 |

### Valeur de retour

La chaîne contenant la représentation encodée en base-64 du tableau d'entrée

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) méthode


Le Base-64 encode une plage d'éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets contenant la plage d'éléments à encoder |
| offset_in | int | Un indice d'un élément du tableau d'entrée où commence la plage à encoder |
| length | int | La longueur de la plage d'éléments à encoder |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Spécifie les options de formatage des données encodées en base-64 |

### Valeur de retour

La chaîne contenant la représentation encodée en base-64 de la plage d'éléments du tableau d'entrée

## Voir aussi

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)