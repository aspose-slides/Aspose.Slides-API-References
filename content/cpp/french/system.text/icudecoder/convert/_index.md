---
title: Convert()
second_title: Référence API Aspose.Slides for C++
description: Convertit des octets en caractères.
type: docs
weight: 66
url: /fr/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Convertit des octets en caractères.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| byteIndex | int | Décalage du tampon d'entrée. |
| byteCount | int | Taille du tampon d'entrée. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tampon de caractères de destination. |
| charIndex | int | Décalage du tableau de destination. |
| charCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne du décodeur après le calcul. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d'octets lus. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères écrits. |
| completed | **bool**\& | Référence à la variable à définir sur vrai si le tampon d'entrée est épuisé, sinon faux. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Convertit des octets en caractères.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| byteCount | int | Taille du tampon d'entrée. |
| chars | char_t * | Tampon de caractères de destination. |
| charCount | int | Taille du tableau de destination. |
| flush | **bool** | Si vrai, nettoie l'état interne du décodeur après le calcul. |
| bytesUsed | int\& | Référence à la variable qui stocke le nombre d'octets lus. |
| charsUsed | int\& | Référence à la variable qui stocke le nombre de caractères écrits. |
| completed | **bool**\& | Référence à la variable à définir sur vrai si le tampon d'entrée est épuisé, sinon faux. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUDecoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)