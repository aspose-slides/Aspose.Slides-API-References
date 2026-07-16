---
title: GetCharCount()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.
type: docs
weight: 79
url: /fr/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Nombre de caractères.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets. |

### Valeur de retour

Nombre de caractères.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Nombre de caractères.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method

Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |

### Valeur de retour

Nombre de caractères.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

Obtenir le nombre de caractères nécessaires pour décoder un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets. |

### Valeur de retour

Nombre de caractères.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UTF7Encoding](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)