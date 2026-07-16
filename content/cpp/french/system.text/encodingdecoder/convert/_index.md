---
title: Convert()
second_title: Référence API Aspose.Slides pour C++
description: Convertit des octets en caractères.
type: docs
weight: 1
url: /fr/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) méthode


Convertit des octets en caractères.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| byteCount | int | Taille du tampon d’entrée. |
| chars | char_t * | Tampon de caractères de destination. |
| charCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l’état interne du décodeur après le calcul. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d’octets lus. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères écrits. |
| completed | **bool**\& | Référence à la variable qui doit être définie sur true si le tampon d’entrée est épuisé et sur false sinon. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) méthode


Convertit des octets en caractères.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| byteIndex | int | Décalage du tampon d’entrée. |
| byteCount | int | Taille du tampon d’entrée. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tampon de caractères de destination. |
| charIndex | int | Décalage du tableau de destination. |
| charCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l’état interne du décodeur après le calcul. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d’octets lus. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères écrits. |
| completed | **bool**\& | Référence à la variable qui doit être définie sur true si le tampon d’entrée est épuisé et sur false sinon. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EncodingDecoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)