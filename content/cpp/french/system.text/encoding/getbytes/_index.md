---
title: GetBytes()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les octets résultant de l'encodage d'un tampon de caractères.
type: docs
weight: 248
url: /fr/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |
| char_index | int | Début de la tranche de caractères. |
| char_count | int | Nombre de caractères à convertir. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour placer les caractères. |
| byte_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caractères à encoder. |
| char_index | int | Début de la tranche de caractères. |
| char_count | int | Nombre de caractères à convertir. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour placer les caractères. |
| byte_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caractères à encoder. |
| char_index | int | Début de la tranche de caractères. |
| char_count | int | Nombre de caractères à convertir. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) pour placer les caractères. |
| byte_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) à encoder. |
| char_index | int | Début de la tranche de caractères. |
| char_count | int | Nombre de caractères à convertir. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour placer les caractères. |
| byte_index | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Encoding::GetBytes(const String\&) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) à encoder. |

### Valeur de retour

[Buffer](../../../system/buffer/) contenant la représentation des caractères encodés.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |
| index | int | Début de la tranche de caractères. |
| count | int | Nombre de caractères à convertir. |

### Valeur de retour

[Buffer](../../../system/buffer/) contenant la représentation des caractères encodés.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caractères à encoder. |
| index | int | Début de la tranche de caractères. |
| count | int | Nombre de caractères à convertir. |

### Valeur de retour

[Buffer](../../../system/buffer/) contenant la représentation des caractères encodés.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caractères à encoder. |
| index | int | Début de la tranche de caractères. |
| count | int | Nombre de caractères à convertir. |

### Valeur de retour

[Buffer](../../../system/buffer/) contenant la représentation des caractères encodés.

## Encoding::GetBytes(ArrayPtr\<char_t\>) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |

### Valeur de retour

[Buffer](../../../system/buffer/) contenant la représentation des caractères encodés.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

Obtient les octets résultant de l'encodage d'un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caractères à encoder. |
| char_count | int | Nombre de caractères à convertir. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) pour placer les caractères. |
| byte_count | int | Taille du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoding](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)