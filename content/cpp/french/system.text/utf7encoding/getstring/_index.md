---
title: GetString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Décode un tampon d'octets en une chaîne.
type: docs
weight: 170
url: /fr/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) méthode


Décode un tampon d'octets en une chaîne.

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| index | int | Décalage du tampon d'entrée. |
| count | int | Taille du tampon d'entrée. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(uint8_t *, int) méthode


Décode un tampon d'octets en une chaîne.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| byte_count | int | Taille du tampon d'entrée. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) méthode


Décode un tampon d'octets en une chaîne.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) pour lire les octets depuis. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) méthode


Décode un tampon d'octets en une chaîne.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) méthode


Décode un tampon d'octets en une chaîne.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) pour lire les octets depuis. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) méthode


Décode un tampon d'octets en une chaîne.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) pour lire les octets depuis. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) méthode


Décode un tampon d'octets en une chaîne.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| index | int | Décalage du tampon d'entrée. |
| count | int | Taille du tampon d'entrée. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) méthode


Décode un tampon d'octets en une chaîne.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| index | int | Décalage du tampon d'entrée. |
| count | int | Taille du tampon d'entrée. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) méthode


Décode un tampon d'octets en une chaîne.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) pour lire les octets depuis. |
| index | int | Décalage du tampon d'entrée. |
| count | int | Taille du tampon d'entrée. |

### Valeur retournée

[String](../../../system/string/) de caractères décodés.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [UTF7Encoding](../)
* Classe [ReadOnlySpan](../../../system/readonlyspan/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)