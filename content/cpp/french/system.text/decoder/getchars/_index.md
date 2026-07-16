---
title: GetChars()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les caractères résultant du décodage d'un tampon.
type: docs
weight: 53
url: /fr/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) méthode


Obtient les caractères résultant du décodage d'un tampon.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |

### Valeur de retour

Nombre de caractères écrits.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) méthode


Obtient les caractères résultant du décodage d'un tampon.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |
| flush | **bool** | Si vrai, nettoie l’état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères écrits.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) méthode


Obtient les caractères résultant du décodage d'un tampon.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| byteCount | int | Input buffer size. |
| chars | char_t * | Destination character buffer. |
| charCount | int | Destination array size. |
| flush | **bool** | Si vrai, nettoie l’état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)