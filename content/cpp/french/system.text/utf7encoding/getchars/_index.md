---
title: GetChars()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les caractères résultant du décodage d'un tampon d'octets.
type: docs
weight: 92
url: /fr/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| byte_index | int | Décalage du tampon d'entrée. |
| byte_count | int | Taille du tampon d'entrée. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) pour mettre les caractères. |
| char_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre de caractères écrits.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| byte_count | int | Taille du tampon d'entrée. |
| chars | char_t * | [Buffer](../../../system/buffer/) pour mettre les caractères. |
| char_count | int | Taille du tampon de sortie. |

### Valeur de retour

Nombre de caractères écrits.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| byte_index | int | Décalage du tampon d'entrée. |
| byte_count | int | Taille du tampon d'entrée. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) pour mettre les caractères. |
| char_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre de caractères écrits.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| index | int | Décalage du tampon d'entrée. |
| count | int | Taille du tampon d'entrée. |

### Valeur de retour

[Buffer](../../../system/buffer/) de caractères décodés.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |

### Valeur de retour

[Buffer](../../../system/buffer/) de caractères décodés.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) méthode

Obtient les caractères résultant du décodage d'un tampon d'octets.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| byte_count | int | Taille du tampon d'entrée. |
| chars | char_t * | [Buffer](../../../system/buffer/) pour mettre les caractères. |
| char_count | int | Taille du tampon de sortie. |

### Valeur de retour

Nombre de caractères écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UTF7Encoding](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)