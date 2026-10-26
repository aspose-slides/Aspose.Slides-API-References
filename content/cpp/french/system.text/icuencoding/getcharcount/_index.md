---
title: GetCharCount()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtenez le nombre de caractères nécessaires pour décoder un tampon d'octets.
type: docs
weight: 53
url: /fr/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets. |

### Valeur de retour

Nombre de caractères.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Nombre de caractères.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |

### Valeur de retour

Nombre de caractères.

## ICUEncoding::GetCharCount(const uint8_t *, int) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets. |

### Valeur de retour

Nombre de caractères.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)